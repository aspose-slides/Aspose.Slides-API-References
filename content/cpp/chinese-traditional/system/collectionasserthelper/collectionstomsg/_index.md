---
title: CollectionsToMsg()
second_title: Aspose.Slides for C++ API 參考文件
description: 將兩個集合序列化為訊息表示形式。
type: docs
weight: 53
url: /zh-hant/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) 方法

將兩個集合序列化為訊息表示形式。

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 預期集合元素類型。 |
| T2 | 實際集合元素類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | 自訂字串，會插入在結果訊息的預期值之前 |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | 預期的集合。 |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | 實際的集合。 |

### 回傳值

使用者友善的集合內容訊息。

## 參見

* 型別定義 [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 結構 [CollectionAssertHelper](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)