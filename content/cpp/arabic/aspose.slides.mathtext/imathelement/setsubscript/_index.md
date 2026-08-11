---
title: SetSubscript()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للـ C++
description: ينشئ مؤشراً سفلياً
type: docs
weight: 79
url: /ar/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) طريقة


ينشئ مؤشراً سفلياً

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | الكتابة السفلية (مؤشر سفلي على اليمين) |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathSubscriptElement](../../imathsubscriptelement/)
## ملاحظات



مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) طريقة


ينشئ مؤشراً سفلياً

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | الكتابة السفلية (مؤشر سفلي على اليمين) |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathSubscriptElement](../../imathsubscriptelement/)
## ملاحظات



مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathSubscriptElement](../../imathsubscriptelement/)
* فئة [IMathElement](../)
* فئة [String](../../../system/string/)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)