---
title: MathBox()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتهيئة MathBox باستخدام العنصر المحدد كوسيط
type: docs
weight: 144
url: /ar/aspose.slides.mathtext/mathbox/mathbox/
---
## MathBox::MathBox(System::SharedPtr\<IMathElement\>) المُنشئ


يقوم بتهيئة [MathBox](../) باستخدام العنصر المحدد كوسيط

```cpp
Aspose::Slides::MathText::MathBox::MathBox(System::SharedPtr<IMathElement> element)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر الأساسي الذي يُطبق عليه الصندوق. يمكن أن يكون فارغًا. |
## Remarks



مثال: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## See Also

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathBox](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)