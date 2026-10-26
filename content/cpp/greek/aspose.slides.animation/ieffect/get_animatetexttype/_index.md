---
title: get_AnimateTextType()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ορίζει έναν τύπο κειμένου κίνησης για το εφέ. Το κείμενο του σχήματος μπορεί να κινείται ανά γράμμα, ανά λέξη ή όλα μαζί. Διαβάστε AnimateTextType.
type: docs
weight: 274
url: /el/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() μέθοδος

Ορίζει έναν τύπο κειμένου κίνησης για το εφέ. Το κείμενο του σχήματος μπορεί να κινείται ανά γράμμα, ανά λέξη ή όλα μαζί. Διαβάστε [AnimateTextType](../../animatetexttype/).

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
```

## Παρατηρήσεις

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Πάρτε το πρώτο εφέ της πρώτης διαφάνειας.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Αλλάξτε τον τύπο κειμένου κίνησης του εφέ σε "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Δείτε επίσης

* Απαρίθμηση [AnimateTextType](../../animatetexttype/)
* Κλάση [IEffect](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)