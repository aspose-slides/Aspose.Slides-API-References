---
title: set_AnimateTextType()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει έναν τύπο κειμένου κίνησης για effect. Το κείμενο shape μπορεί να αναπαραχθεί ανά γράμμα, ανά λέξη ή όλα μαζί. Γράψτε AnimateTextType.
type: docs
weight: 287
url: /el/aspose.slides.animation/effect/set_animatetexttype/
---
## Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) μέθοδος

Ορίζει έναν τύπο κειμένου κίνησης για το Effect. Το κείμενο Shape μπορεί να αναπαραχθεί ανά γράμμα, ανά λέξη ή όλα μαζί. Γράψτε [AnimateTextType](../../animatetexttype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value) override
```

## Παρατηρήσεις

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Λάβετε το πρώτο εφέ της πρώτης διαφάνειας.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Αλλάξτε τον τύπο κειμένου κίνησης του εφέ σε "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Δείτε επίσης

* Enum [AnimateTextType](../../animatetexttype/)
* Class [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)