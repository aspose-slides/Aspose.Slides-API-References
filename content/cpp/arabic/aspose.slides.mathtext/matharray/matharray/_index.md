---
title: MathArray()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: ينشئ مصفوفة رياضية ويضع العنصر المحدد فيها
type: docs
weight: 144
url: /ar/aspose.slides.mathtext/matharray/matharray/
---
## MathArray::MathArray(System::SharedPtr\<IMathElement\>) المُنشئ


ينشئ مصفوفة رياضية ويضع العنصر المحدد فيها

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<IMathElement> element)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر الذي سيُوضع في المصفوفة |
## ملاحظات



مثال: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
```

## MathArray::MathArray(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) المُنشئ


ينشئ مصفوفة رياضية ويضع العناصر المحددة فيها

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> elements)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| elements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | العناصر التي ستُوضع في المصفوفة |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathArray](../)
* فئة [IEnumerable](../../../system.collections.generic/ienumerable/)
* مساحة الأسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)