# Vertex Cover Solver with Grover's Algorithm

## 題目簡介
給定一張圖與目標大小 k，找出所有大小為 k 的 vertex cover。

使用 Grover's Algorithm 加速搜尋，並在 Qiskit 模擬器上執行。

針對四個案例（case1 ~ case4）分別執行：

* 顯示量子電路圖

* 顯示量測結果的直方圖

* 顯示所有合法 vertex cover 的節點圖

##  執行環境
* Python 3.8+

* Qiskit

* NetworkX

* Matplotlib

* Jupyter Notebook（或支援 %matplotlib inline 的 Python IDE，如 Google Colab）

先安裝必要套件：
```
  pip install qiskit networkx matplotlib
```
若在 Colab 執行，在程式前加上：
```
!pip install qiskit networkx matplotlib
```

##  執行方式

直接執行 main.py 或在 Jupyter/Colab 中貼上完整程式碼。

本程式會依序處理四組資料：

* case1：簡單圖，共 5 個節點

* case2：樹與環的結合，共 7 節點

* case3：包含三角形與交錯邊

* case4：中心點大量連線的星狀結構

每組都會顯示：

1. 量子線路圖

2. Grover 演算法量測結果直方圖

3. 每個合法 Vertex Cover 的節點視覺化圖
