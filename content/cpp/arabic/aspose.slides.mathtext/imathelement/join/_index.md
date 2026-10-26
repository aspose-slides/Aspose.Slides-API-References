---
title: Join()
second_title: Aspose.Slides لمرجع واجهة برمجة التطبيقات C++
description: يقوم بدمج عنصر رياضي وتشكيل كتلة رياضية
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) طريقة


يقوم بدمج عنصر رياضي وتشكيل كتلة رياضية

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```


### الوسائط

| المعامل | نوع | الوصف |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | العنصر الذي سيتم دمجه |

### قيمة الإرجاع

كائن [IMathBlock](../../imathblock/) جديد يحتوي على هذه المثيلة والوسيط المحدد
## ملاحظات



مثال: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) طريقة


يقوم بدمج نص رياضي وتشكيل كتلة رياضية

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```


### الوسائط

| المعامل | نوع | الوصف |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | النص الرياضي الذي سيتم دمجه |

### قيمة الإرجاع

كائن [IMathBlock](../../imathblock/) جديد يحتوي على هذه المثيلة والوسيط المحدد
## ملاحظات



مثال: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## أنظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [IMathBlock](../../imathblock/)
* الفئة [IMathElement](../)
* الفئة [String](../../../system/string/)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)