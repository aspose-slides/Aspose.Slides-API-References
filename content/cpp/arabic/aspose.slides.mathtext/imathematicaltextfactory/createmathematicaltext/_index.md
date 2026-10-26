---
title: CreateMathematicalText()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إنشاء عنصر نص رياضي فارغ
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathematicaltextfactory/createmathematicaltext/
---
## IMathematicalTextFactory::CreateMathematicalText() method


إنشاء عنصر نص رياضي فارغ

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText()=0
```


### قيمة الإرجاع

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(char16_t) method


إنشاء عنصر نص رياضي بالقيمة المحددة

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol)=0
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathSymbol | char16_t | رمز واحد لاستخدامه كقيمة نصية |

### قيمة الإرجاع

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String) method


إنشاء عنصر نص رياضي فارغ بالقيمة المحددة

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText)=0
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | قيمة النص |

### قيمة الإرجاع

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) method


إنشاء عنصر نص رياضي فارغ بالقيمة المحددة وإعدادات التنسيق

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)=0
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | قيمة النص |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | إعدادات تنسيق النص |

### قيمة الإرجاع

new Mathematical Text

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [IMathematicalText](../../imathematicaltext/)
* الفئة [IMathematicalTextFactory](../)
* الفئة [String](../../../system/string/)
* الفئة [IPortionFormat](../../../aspose.slides/iportionformat/)
* مجال الاسم [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)