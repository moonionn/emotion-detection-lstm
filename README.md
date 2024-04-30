## 情緒識別 LSTM 模型

### 項目概述
這個項目使用 LSTM 神經網絡來識別文本中的情緒。
目標是能夠準確預測文本表達的情緒，如快樂、憤怒、驚訝等。

### 資料集
資料集包括標記為不同情緒的句子。我們有三個主要的資料集文件：`train.txt`，`test.txt`和`val.txt`。

### 預處理
在`preprocessing.ipynb`和`txtTOcsv.ipynb`筆記本中，我們進行了資料清洗和格式轉換。
步驟包括去除停用詞、標點符號和低頻詞。

### 模型訓練
使用 GloVe 預訓練詞嵌入和 LSTM 層構建了模型。
模型訓練的細節記錄在`LSTM-glove.ipynb`和`LSTM-model.ipynb`筆記本中。

### 訓練結果
兩個模型均顯示出良好的性能，其中 LSTM-model在測試集上達到了 91.60% 的準確率，優於 LSTM-GloVe 模型。每個情緒類別的精確度、召回率和 F1 分數均達到了良好水平。

### 結論
模型的性能證明了使用 LSTM 對於情緒分類的有效性。
未來工作可能包括更進一步平衡數據集、嘗試不同的模型架構或調整模型的超參數。

---

感謝您關注這個項目。如果您有任何建議或問題，請隨時開啟 issue 或提交 pull request。

