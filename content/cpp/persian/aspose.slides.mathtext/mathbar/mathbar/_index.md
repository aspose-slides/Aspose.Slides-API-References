---
title: MathBar()
second_title: مرجع API Aspose.Slides برای C++
description: MathBar را با خط فوقانی (موقعیت بالا) مقداردهی می‌کند
type: docs
weight: 40
url: /fa/aspose.slides.mathtext/mathbar/mathbar/
---
## MathBar::MathBar(System::SharedPtr\<IMathElement\>) سازنده

[MathBar](../) را با خط فوقانی (موقعیت بالا) مقداردهی می‌کند

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر پایه‌ای که نوار بر روی آن اعمال می‌شود |

## توضیحات



مثال: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBar::MathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) سازنده

[MathBar](../) را با موقعیت مشخص مقداردهی می‌کند

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر پایه‌ای که نوار بر روی آن اعمال می‌شود |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | موقعیت خط نوار |

## توضیحات



مثال: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"), MathTopBotPositions::Bottom);
```

## موارد مرتبط

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBar](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)