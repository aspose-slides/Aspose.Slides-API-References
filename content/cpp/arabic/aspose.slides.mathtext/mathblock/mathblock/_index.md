---
title: MathBlock()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تهيئ مثلاً جديداً من الفئة MathBlock.
type: docs
weight: 66
url: /ar/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() منشئ

تهيئ مثلاً جديداً من الفئة [MathBlock](../).

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## ملاحظات

مثال:
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) منشئ

ينشئ كتلة رياضية جديدة ويضع العنصر المحدد فيها

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر الرياضي لوضعه في الكتلة |

## ملاحظات

مثال:
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) منشئ

ينشئ كتلة رياضية جديدة ويضع العناصر المحددة فيها

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | العناصر الرياضية لوضعها في الكتلة |

## ملاحظات

مثال:
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الفئة [MathBlock](../)
* الفئة [IMathElement](../../imathelement/)
* الفئة [IEnumerable](../../../system.collections.generic/ienumerable/)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)