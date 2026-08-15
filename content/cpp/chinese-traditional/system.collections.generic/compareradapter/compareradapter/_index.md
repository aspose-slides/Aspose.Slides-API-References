---
title: ComparerAdapter()
second_title: Aspose.Slides for C++ API 參考
description: 在沒有可用的比較器時建構適配器。
type: docs
weight: 1
url: /zh-hant/system.collections.generic/compareradapter/compareradapter/
---
## ComparerAdapter::ComparerAdapter() 建構子


在沒有可用比較器的情況下建構適配器。

```cpp
System::Collections::Generic::ComparerAdapter<T>::ComparerAdapter()
```

## ComparerAdapter::ComparerAdapter(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) 建構子


建構適配器。

```cpp
System::Collections::Generic::ComparerAdapter<T>::ComparerAdapter(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | 要使用的比較器物件。 |

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IComparer](../../icomparer/)
* 結構 [ComparerAdapter](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)