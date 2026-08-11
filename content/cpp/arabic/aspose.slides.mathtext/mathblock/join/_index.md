---
title: Join()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يجمع عنصرًا رياضيًا مع هذه الكتلة الرياضية
type: docs
weight: 183
url: /ar/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) طريقة


يجمع عنصرًا رياضيًا مع هذه الكتلة الرياضية

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```


### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر الذي سيتم دمجه |

### قيمة الإرجاع

العنصر الحالي من [IMathBlock](../../imathblock/)
## ملاحظات



مثال: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) طريقة


يجمع نصًا رياضيًا مع هذه الكتلة الرياضية

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```


### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | النص الرياضي الذي سيتم دمجه |

### قيمة الإرجاع

كائن جديد من نوع [IMathBlock](../../imathblock/) يحتوي على هذه المثيل والوسيط المحدد
## ملاحظات



مثال: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## انظر أيضا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathBlock](../../imathblock/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathBlock](../)
* فئة [String](../../../system/string/)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)