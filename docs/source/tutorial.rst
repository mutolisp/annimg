.. 「數位資源回收器」三分鐘快速上手教學


******************
給初學者的 How-To
******************

1. 安裝
=======

安裝「數位資源回收器(AnnImg)」步驟十分簡單，
只需要兩個步驟的口訣：連網址、拖連結。詳細說明如下：

#. 連到 http://twebi.net/imgAnn/ann.html

#. 把 **AnnImg** 連結拖到書籤列

   .. figure:: images/drag_to_bookmark_bar.png
      :scale: 35%
      :alt: drag to install

      使用拖拉至書籤列安裝(以 Google Chrome 為例)

.. note::

   #. 如果你的瀏覽器沒有書籤列的話，請記得開啟。以 Google Chrome 為例，
      請在「檢視」中開啟「顯示書籤列」(參考下圖)，詳細說明請參考
      「`如何使用書籤列 <https://support.google.com/chrome/answer/95745?hl=zh-Hant>`_」

      .. figure:: images/open_bookmark_bar.png
         :scale: 35%
         :alt: 顯示書籤列

         Google Chrome 顯示書籤列

   #. 目前已知 Safari 10.x 不支援

2. 使用
=======

數位資源回收器可針對任意網路上的圖片進行人工判讀及標註，
使用時只需要透過瀏覽器輸入照片的網址，再點選書籤列上的
**AnnImg** ，即可開始標註。而網址中解析度大於 300 x 300 px 
的影像則會自動帶入數位資源回收器，並組成影像清單，
接下來再標記影像，手動輸入影像中標註事件的代表意義即可。
以下舉例說明如何標註照片中的事件：

2.1 帶入影像
------------

我們以在 facebook 這張 `照片 <https://www.facebook.com/photo.php?fbid=973646572767671&set=pcb.1435326166499709&type=3&theater>`_ 為例:

   .. figure:: images/example1.png
      :scale: 35%
      :alt: 煤山雀吃雲杉的種子

這張照片是煤山雀吃臺灣雲杉的記錄，要帶入這張影像只要先使用瀏覽器開啟 facebook 照片網址，
再點選書籤列上之前加入的 **AnnImg** 連結即可，如下圖：

   .. figure:: images/ex1_trigger_annimg.png
      :scale: 35%
      :alt: 煤山雀吃雲杉的種子，帶入 AnnImg

若成功帶入影像後，會自動前往數位資源回收器的伺服器頁面，進入功能主面板，如下圖

   .. figure:: images/annimg_page.png
      :scale: 35%
      :alt: 煤山雀吃雲杉的種子，帶入 AnnImg


2.2 標記影像
------------

接下來在標記影像這部份，先使用滑鼠點擊 create new token (快速鍵 C)，
此時影像會蒙上一層灰，再以滑鼠圈選出感興趣的標的物，稱為「標記(token)」。
用來圈選的空心方塊稱為「邊界框(bounding box; bbox）」，
使用者可隨時拖拉調整邊界框的位置與大小，如下圖：


   .. figure:: images/ex1_bbox.png
      :scale: 35%
      :alt: 使用邊界框建立標記

      使用邊界框建立標記



.. note::

   #. 有些網頁儲存照片資料結構會有一些預先的縮圖，例如 `facebook <https://www.facebook.com>`_ 及
      `flickr <http://flickr.com>`_ 等，此時若要載入較高解析度的照片時，
      可使用鍵盤的左右鍵或用滑鼠點擊 prev / next 來切換影像。

   #. 數位資源回收器對於某些網頁可能不適用，目前針對自然攝影中心及 flickr 皆有做過特別處理，
      遇到無法使用的照片網頁請回報，我們將會改進程式的適用性


