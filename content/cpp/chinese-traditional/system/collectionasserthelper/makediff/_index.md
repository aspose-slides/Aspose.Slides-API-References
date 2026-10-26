---
title: MakeDiff()
second_title: Aspose.Slides for C++ API 參考
description: 計算兩個集合之間的 'diff'。對每個集合的每個元素作為鍵，若元素在 \"expected\" 集合中出現次數較多，結果值為正；若元素在 \"actual\" 集合中出現次數較多，結果值為負；若兩個集合中出現次數相等，結果為零。
type: docs
weight: 1
url: /zh-hant/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) 方法


計算兩個集合之間的「diff」。對於每個集合的每個元素作為鍵，若元素在「expected」集合中出現次數較多，結果值為正；若在「actual」集合中出現次數較多，結果值為負；若兩個集合中出現次數相等，結果為零。

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T1 | 預期集合的元素類型。 |
| T2 | 實際集合的元素類型。 |

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | 預期集合。 |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | 實際集合。 |

### 傳回值

依上述規則的每個值比較結果的映射。

## 另請參閱

* Typedef [SharedPtr](../../sharedptr/)
* Class [Dictionary](../../../system.collections.generic/dictionary/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)