---
title: set_AnimateTextType()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ορίζει έναν τύπο κίνησης κειμένου για το εφέ. Το κείμενο του σχήματος μπορεί να ανιμαριστεί ανά γράμμα, ανά λέξη ή όλα μαζί. Γράψτε AnimateTextType.
type: docs
weight: 287
url: /el/aspose.slides.animation/ieffect/set_animatetexttype/
---
## IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) μέθοδος

Ορίζει έναν τύπο κίνησης κειμένου για το εφέ. Το κείμενο του σχήματος μπορεί να ανιμαριστεί ανά γράμμα, ανά λέξη ή όλα μαζί. Γράψτε [AnimateTextType](../../animatetexttype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value)=0
```

## Παρατηρήσεις


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Λάβετε το πρώτο εφέ της πρώτης διαφάνειας.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Αλλάξτε τον τύπο κίνησης κειμένου του εφέ σε "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Δείτε επίσης

* Enum [AnimateTextType](../../animatetexttype/)
* Κλάση [IEffect](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)