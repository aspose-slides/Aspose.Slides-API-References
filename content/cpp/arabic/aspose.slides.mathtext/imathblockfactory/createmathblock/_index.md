---
title: CreateMathBlock()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إنشاء كتلة رياضية
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathblockfactory/createmathblock/
---
## IMathBlockFactory::CreateMathBlock() طريقة

إنشاء كتلة رياضية

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock()=0
```

### قيمة الإرجاع

كتلة رياضية جديدة

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) طريقة

إنشاء كتلة رياضية ووضع العنصر بداخلها

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر رياضي |

### قيمة الإرجاع

كتلة رياضية جديدة

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) طريقة

إنشاء كتلة رياضية ووضع العناصر بداخلها

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | عناصر رياضية |

### قيمة الإرجاع

كتلة رياضية جديدة

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathBlock](../../imathblock/)
* فئة [IMathBlockFactory](../)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathElementCollection](../../imathelementcollection/)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)