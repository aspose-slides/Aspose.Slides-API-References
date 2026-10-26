---
title: ValueTuple
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للـ C++
description: الفئة التي تمثل بنية بيانات ValueTuple.
type: docs
weight: 1444
url: /ar/system/valuetuple/
---
## فئة ValueTuple

الفئة التي تمثّل بنية بيانات [ValueTuple](./).

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## الطرق

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | يحدد ما إذا كان الكائن الحالي والكائن المحدد متطابقين. |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() | يحصل على المرجع إلى قيمة مكوّن كائن [ValueTuple](./). |
| const std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() const | يحصل على قيمة مكوّن كائن [ValueTuple](./). |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | يفكّ بنية الكائن إلى هذا الـ value tuple. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | يرجع مرجعًا إلى كائن [TypeInfo](../typeinfo/) الذي يمثل معلومات نوع الفئة [ValueTuple](./). |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) | ينشئ كائن tuple. |

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)