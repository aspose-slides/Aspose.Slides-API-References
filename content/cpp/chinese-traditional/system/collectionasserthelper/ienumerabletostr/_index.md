---
title: IEnumerableToStr()
second_title: Aspose.Slides for C++ API 參考文件
description: 透過串接元素的字串表示，將集合轉換為字串。
type: docs
weight: 40
url: /zh-hant/system/collectionasserthelper/ienumerabletostr/
---
## CollectionAssertHelper::IEnumerableToStr(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T\>\>\&) 方法

透過串接元素的字串表示，將集合轉換為字串。

```cpp
template<typename T> static System::String System::CollectionAssertHelper::IEnumerableToStr(const System::SharedPtr<System::Collections::Generic::IEnumerable<T>> &ie)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 集合元素類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ie | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | 要檢查的集合。 |

### 返回值

集合的合併值。

## 另見

* 類型別名 [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 結構 [CollectionAssertHelper](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)