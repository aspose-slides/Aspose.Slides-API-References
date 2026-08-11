---
title: MathBar()
second_title: مرجع Aspose.Slides للغة C++
description: يقوم بتهيئة MathBar مع شَرطَة علوية (الموضع العلوي)
type: docs
weight: 40
url: /ar/aspose.slides.mathtext/mathbar/mathbar/
---
## MathBar::MathBar(System::SharedPtr\<IMathElement\>) منشئ


يقوم بتهيئة [MathBar](../) مع شَرطَة علوية (الموضع العلوي)

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر الأساسي الذي يُطبق عليه الشريط |
## ملاحظات



مثال: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBar::MathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) منشئ


يقوم بتهيئة [MathBar](../) باستخدام موضع محدد

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر الأساسي الذي يُطبق عليه الشريط |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | موضع خط الشريط. |
## ملاحظات



مثال: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"), MathTopBotPositions::Bottom);
```

## انظر أيضًا

* تعداد [MathTopBotPositions](../../mathtopbotpositions/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathBar](../)
* مساحة اسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)