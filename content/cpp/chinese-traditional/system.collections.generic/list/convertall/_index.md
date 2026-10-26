---
title: ConvertAll()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立一個已轉換為不同類型的元素列表。
type: docs
weight: 352
url: /zh-hant/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) 方法

建立一個已轉換為不同類型的元素列表。

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| OutputType | 輸出列表元素類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | 用於項目轉換的轉換器。 |

### 回傳值

新建立的已轉換元素列表。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Converter](../../../system/converter/)
* 類別 [List](../)
* 命名空間 [System::Collections::Generic](../../)
* 程式庫 [Aspose.Slides](../../../)