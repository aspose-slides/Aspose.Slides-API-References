---
title: "System::Collections::Generic::Details"
second_title: "Aspose.Slides for C++ API 參考"
description: 
type: docs
weight: 352
url: /zh-hant/system.collections.generic.details/
---
## 類別

| 類別 | 說明 |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | Enumerable 用於 IEnumerable.Cast() 與 IEnumerable.OfType() 擴充方法。 |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | Enumerable 用於 IEnumerable.Select() 擴充方法。 |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | Enumerator 用於 IEnumerable.Cast() 擴充方法。 |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | Enumerator 用於 IEnumerable.OfType() 擴充方法。 |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | Enumerator 用於 IEnumerable.Select() 擴充方法。 |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |

## 結構

| 結構 | 說明 |
| --- | --- |
| [ComparerType](./comparertype/) | 使用「less」語意比較元素。 |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | 使用「less」語意比較元素。 |
| [has_method_compareto](./has_method_compareto/) | 檢查指定類型中是否存在 CompareTo 方法。若存在，繼承 std::true_type，否則繼承 std::false_type。可在 std::enable_if 中使用。 |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | 檢查指定類型中是否存在 CompareTo(SharedPtr<T>) 方法。若存在，繼承 std::true_type，否則繼承 std::false_type。可於 std::enable_if 中使用。 |
| [IsEqualExist](./isequalexist/) | 檢查類型是否提供 operator ==。 |

## 函式

| 函式 | 說明 |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | 檢查索引是否超出容器範圍（不含容器大小）。 |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | 檢查索引是否超出容器範圍（不含容器大小）。 |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | 檢查索引是否超出容器範圍（包含容器大小）。 |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | 檢查索引是否超出容器範圍（包含容器大小）。 |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | 輔助函式，用於判斷特定類別是否具有 operator ==。 |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | 輔助函式，用於判斷特定類別是否具有 operator ==。 |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | 嘗試取得集合的第一個元素。 |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | 嘗試取得集合中符合謂詞函式的第一個元素。 |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | 嘗試取得集合的最後一個元素。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | 用於檢查 operator == 是否存在的測試型別別名。 |