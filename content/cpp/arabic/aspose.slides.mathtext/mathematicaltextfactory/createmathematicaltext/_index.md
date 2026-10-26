---
title: CreateMathematicalText()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إنشاء عنصر نص رياضي فارغ
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/mathematicaltextfactory/createmathematicaltext/
---
## MathematicalTextFactory::CreateMathematicalText() طريقة

إنشاء عنصر نص رياضي فارغ

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText() override
```

### قيمة الإرجاع

جديد Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(char16_t) طريقة

إنشاء عنصر نص رياضي بالقيمة المحددة

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol) override
```

### معاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| mathSymbol | char16_t | رمز واحد لاستخدامه كقيمة نصية |

### قيمة الإرجاع

جديد Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String) طريقة

إنشاء عنصر نص رياضي فارغ بالقيمة المحددة

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText) override
```

### معاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | قيمة النص |

### قيمة الإرجاع

جديد Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) طريقة

إنشاء عنصر نص رياضي فارغ بالقيمة المحددة وخصائص التنسيق

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat) override
```

### معاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | قيمة النص |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | إعدادات تنسيق النص |

### قيمة الإرجاع

جديد Mathematical Text

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathematicalText](../../imathematicaltext/)
* فئة [MathematicalTextFactory](../)
* فئة [String](../../../system/string/)
* فئة [IPortionFormat](../../../aspose.slides/iportionformat/)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)