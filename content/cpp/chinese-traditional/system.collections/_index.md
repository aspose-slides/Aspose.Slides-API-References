---
title: "System::Collections"
second_title: Aspose.Slides for C++ API 參考手冊
description: 
type: docs
weight: 300
url: /zh-hant/system.collections/
---
## 類別

| 類別 | 描述 |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/)的位元集合，可透過索引位址存取。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標將其作為參數傳遞給函式。 |
| [BitArrayPtr](./bitarrayptr/) | 指向 [BitArray](./bitarray/) 的指標。此類型是用於管理其他物件刪除的指標。它應分配於堆疊上，並以值傳遞或 const 參考方式傳遞給函式。 |
| [CollectionBase](./collectionbase/) | 提供一個強型別集合的抽象基底類別。 |
| [ICollection](./icollection/) | 定義非泛型集合介面。 |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) 是所有可列舉之非泛型集合的基礎介面。 |
| [IEnumerator](./ienumerator/) | 可用於遍歷某些元素的列舉器介面。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標將其作為參數傳遞給函式。 |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | 建立非泛型 [IEnumerator](./ienumerator/) 實作於通用 Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) 之上的封裝器──用於參考型別的封裝器。 |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | 建立非泛型 [IEnumerator](./ienumerator/) 實作於通用 Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) 之上的封裝器──用於值型別的封裝器。 |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) 代表一個可透過索引個別存取的非泛型物件集合。 |
| [IListImplRefType](./ilistimplreftype/) | 在 [System::Collections::Generic::List](../system.collections.generic/list/) 物件上實作 [System::Collections::IList](./ilist/) 介面的存根，供參考型別使用的實作。 |
| [IListImplValueType](./ilistimplvaluetype/) | 在 [System::Collections::Generic::List](../system.collections.generic/list/) 物件上實作 [System::Collections::IList](./ilist/) 介面的存根，供值型別使用的實作。 |
| [IListWrapper](./ilistwrapper/) | 支援從泛型轉換為非泛型集合的介面。 |
| [Invalidatable](./invalidatable/) | 使能透過 [InvalidatableTracker](./invalidatabletracker/) 物件追蹤其衍生類別狀態的類別。 |
| [InvalidatableTracker](./invalidatabletracker/) | 實作 [Invalidatable](./invalidatable/) 物件追蹤器的類別。 |