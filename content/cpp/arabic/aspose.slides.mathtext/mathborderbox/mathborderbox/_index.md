---
title: MathBorderBox()
second_title: مرجع API ل Aspose.Slides للغة C++
description: ينشئ عنصر MathBorderBox بحد مستطيل
type: docs
weight: 222
url: /ar/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) المنشئ

يُنشئ عنصر [MathBorderBox](../) بحد مستطيل

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر الأساسي الذي يُطبّق عليه صندوق الحدود. يمكن أن يكون فارغًا. |

## ملاحظات



مثال: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) المنشئ

يُنشئ عنصر [MathBorderBox](../)

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر الأساسي الذي يُطبّق عليه صندوق الحدود |
| hideTop | **bool** | إخفاء الحافة العلوية |
| hideBottom | **bool** | إخفاء الحافة السفلية |
| hideLeft | **bool** | إخفاء الحافة اليسرى |
| hideRight | **bool** | إخفاء الحافة اليمنى |
| strikethroughHorizontal | **bool** | خط أفقي |
| strikethroughVertical | **bool** | خط عمودي |
| strikethroughBottomLeftToTopRight | **bool** | خط من أسفل اليسار إلى أعلى اليمين |
| strikethroughTopLeftToBottomRight | **bool** | خط من أعلى اليسار إلى أسفل اليمين |

## ملاحظات



مثال: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الفئة [IMathElement](../../imathelement/)
* الفئة [MathBorderBox](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)