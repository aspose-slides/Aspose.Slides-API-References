---
title: ValueTuple
second_title: Aspose.Slides for C++ API संदर्भ
description: एक वर्ग जो ValueTuple डेटा संरचना का प्रतिनिधित्व करता है।
type: docs
weight: 1444
url: /hi/system/valuetuple/
---
## ValueTuple क्लास

Class that represents a [ValueTuple](./) data structure.

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## विधियाँ

| विधि | वर्णन |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | निर्धारित करता है कि वर्तमान और निर्दिष्ट वस्तुएँ समान हैं या नहीं। |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() | [ValueTuple](./) वस्तु के घटक के मान के संदर्भ को प्राप्त करता है। |
| const std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() const | [ValueTuple](./) वस्तु के घटक का मान प्राप्त करता है। |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | ऑब्जेक्ट को इस वैल्यू टुपल में विघटित करता है। |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | [TypeInfo](../typeinfo/) वस्तु का एक संदर्भ लौटाता है जो [ValueTuple](./) क्लास प्रकार की जानकारी का प्रतिनिधित्व करता है। |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) | एक टुपल वस्तु बनाता है। |
## संबंधित देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)