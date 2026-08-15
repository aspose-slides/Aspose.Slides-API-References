---
title: ValueTuple
second_title: Aspose.Slides for C++ API 參考
description: 表示 ValueTuple 資料結構的類別。
type: docs
weight: 1444
url: /zh-hant/system/valuetuple/
---
## ValueTuple 類別

此類別代表 [ValueTuple](./) 資料結構。

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## 方法

| 方法 | 說明 |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | 判斷目前物件與指定物件是否相同。 |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() | 取得 [ValueTuple](./) 物件之元件的值的參考。 |
| const std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() const | 取得 [ValueTuple](./) 物件之元件的值。 |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 將物件解構為此值元組。 |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | 傳回指向表示 [ValueTuple](./) 類別型別資訊的 [TypeInfo](../typeinfo/) 物件的參考。 |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) | 建構一個元組物件。 |

## 另請參閱

* 命名空間 [System](../)
* 程式庫 [Aspose.Slides](../../)