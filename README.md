# Data Structure and Algorithm Homework
資料結構與演算法課程作業

## 目錄
* [內容](#內容)
* [使用](#使用)
* [執行](#執行)

## 內容
  <table>
    <tr>
      <th>作業分類</th>
      <th>目錄</th>
      <th>說明</th>
      <th>截止日期</th>
      <th>說明</th>
    </tr>
    <tr>
      <td>105上學期作業1</td>
      <td>sort</td>
      <td>選擇與氣泡排序</td>
      <td>2016/09/30</td>
      <td>包含：<br/>Bubble sort（氣泡排序）<br/>Selection sort（選擇排序）<br/>Insertion sort（插入排序）<br/>Cocktail sort（雞尾酒排序）<br/>Bucket sort（桶子排序）<br/>Counting sort（計數排序）<br/>Merge sort（合併排序）<br/>Binary search tree（二元搜尋樹）<br/>Comb sort（梳排序）<br/>Radix sort（基數排序）<br/>Gnome sort（地精排序）<br/>Odd-even sort（奇偶排序）<br/>Shell sort（希爾排序）<br/>Quick sort（快速排序）<br/>Heap sort（堆積排序）<br/>Stooge sort（臭皮匠排序）<br/>Bogo sort（無限猴子排序）<br/><br/>※有可能翻譯導致實作問題<br/>※早期作品，實作效能可能有差<br/>※沒有收錄Sleep sort（睡眠排序）</td>
    </tr>
    <tr>
      <td>105上學期作業2</td>
      <td>magic_square</td>
      <td>魔方陣</td>
      <td>2016/10/22</td>
      <td>包含所有奇數、單偶數、雙偶數</td>
    </tr>
    <tr>
      <td>105上學期作業3</td>
      <td>maze</td>
      <td>老鼠走迷宮</td>
      <td>2016/11/20</td>
      <td>使用希爾伯特曲線生成，拆除、補充牆壁的方式生成迷宮。目錄有附範例迷宮檔案。而且可以改顏色。<br/><br/>※動畫速度稍慢</td>
    </tr>
    <tr>
      <td>105上學期作業4</td>
      <td>infix_transform</td>
      <td>前、中、後序轉換</td>
      <td>2016/12/10</td>
      <td>沒有特別增加的功能。</td>
    </tr>
    <tr>
      <td>105上學期作業5</td>
      <td>linked_list</td>
      <td>串列結構</td>
      <td>2016/01/08</td>
      <td>結構經過封裝。且採用C++ Template方式寫成。<br/><br/>※有附串列堆疊，但顯示方式稍差。</td>
    </tr>
    <tr>
      <td>105下學期作業1</td>
      <td>binary_search_tree</td>
      <td>二元搜尋樹結構（上）</td>
      <td>2017/03/13</td>
      <td>結構經過封裝。且採用C++ Template方式寫成。遍歷使用Callback函數指標。<br/><br/>※初次提交時沒有完成下半部的功能。</td>
    </tr>
    <tr>
      <td>105下學期作業2</td>
      <td>binary_search_tree</td>
      <td>二元搜尋樹結構（下）</td>
      <td>2017/03/27</td>
      <td>同「105下學期作業1」<br/><br/>※忘記完成階層走訪的功能。<br/>※初次提交未完成非遞迴刪除，目前已完成。</td>
    </tr>
    <tr>
      <td>105下學期作業3</td>
      <td>sort</td>
      <td>二元搜尋樹、堆積排序</td>
      <td>2017/03/27</td>
      <td>※與「105上學期作業1」性質重複。</td>
    </tr>
    <tr>
      <td>105下學期作業4</td>
      <td>spanning_tree</td>
      <td>最小生成樹</td>
      <td>2017/05/20</td>
      <td>包含：<br/>1. Krukal's Algorithm(STL Sort)<br/>2. Krukal's Algorithm(Quick Sort)<br/>3. Krukal's Algorithm(Bubble Sort)<br/>4. Krukal's Algorithm(Linear Search)<br/>5. Krukal's Algorithm(Heap)<br/>6. Prim's Algorithm<br/><br/>※含一個 PDF 分析圖表。</td>
    </tr>
    <tr>
      <td>105下學期作業5</td>
      <td>shortest_paths</td>
      <td>最短路徑、遞移封閉</td>
      <td>2017/06/03</td>
      <td>※除了最小權重外，也包含路徑紀錄。</td>
    </tr>
    <tr>
      <td>105下學期作業6</td>
      <td>sort2</td>
      <td>其他排序</td>
      <td>2017/06/22</td>
      <td>包含：<br/>Bubble sort（氣泡排序）<br/>Selection sort（選擇排序）<br/>Insertion sort（插入排序）<br/>Merge sort（合併排序）<br/>Radix sort（基數排序）<br/>Quick sort（快速排序）<br/>Heap sort（堆積排序）<br/><br/>※這個是sort的部分重製版。<br/>※其中Merge, Quick sort包含遞迴、與非遞迴版本。<br/>※Heap sort建立堆積採Restore方法<br/>※修改Radix sort的空間配置方法</td>
    </tr>
  </table>

## 使用
本專案使用 Visual Studio 2015 撰寫。開啟時請注意版本。

另外使用了 C++ Form 的內容。需確認是否安裝正確。

## 執行
每個專案底下的 Release/ 目錄包含了 .exe 的獨立執行檔案。
