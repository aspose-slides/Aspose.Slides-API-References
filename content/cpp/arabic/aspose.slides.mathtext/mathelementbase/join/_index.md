---
title: Join()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للـ C++
description: ينضم إلى عنصر رياضي ويكوّن كتلة رياضية
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) طريقة


ينضم إلى عنصر رياضي ويكوّن كتلة رياضية

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر المراد ربطه |

### قيمة الإرجاع

كائن [IMathBlock](../../imathblock/) جديد يحتوي على هذه المثيل والوسيط المحدد
## ملاحظات



مثال: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) طريقة


ينضم إلى نص رياضي ويكوّن كتلة رياضية

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | النص الرياضي المراد ربطه |

### قيمة الإرجاع

كائن [IMathBlock](../../imathblock/) جديد يحتوي على هذه المثيل والوسيط المحدد
## ملاحظات



مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathBlock](../../imathblock/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathElementBase](../)
* فئة [String](../../../system/string/)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)