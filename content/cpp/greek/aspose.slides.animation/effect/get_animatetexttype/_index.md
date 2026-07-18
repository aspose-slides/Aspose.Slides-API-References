---
title: get_AnimateTextType()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Ορίζει έναν τύπο κίνησης κειμένου για effect. Το κείμενο του σχήματος μπορεί να αναπαραχθεί με κίνηση ανά γράμμα, ανά λέξη ή όλα μαζί. Διαβάστε AnimateTextType.
type: docs
weight: 274
url: /el/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() μέθοδος

Ορίζει έναν τύπο κίνησης κειμένου για το Effect. Το κείμενο του σχήματος μπορεί να αναπαραχθεί με κίνηση ανά γράμμα, ανά λέξη ή όλα μαζί. Διαβάστε [AnimateTextType](../../animatetexttype/).

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
```

## Παρατηρήσεις

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Αποκτήστε το πρώτο εφέ της πρώτης διαφάνειας.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Αλλάξτε τον τύπο κίνησης κειμένου του εφέ σε "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Δείτε επίσης

* Απαρίθμηση [AnimateTextType](../../animatetexttype/)
* Κλάση [Effect](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)