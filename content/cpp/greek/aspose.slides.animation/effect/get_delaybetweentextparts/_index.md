---
title: get_DelayBetweenTextParts()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει μια καθυστέρηση μεταξύ των κινούμενων τμημάτων κειμένου (λέξεων ή γραμμάτων). Μια θετική τιμή καθορίζει το ποσοστό της διάρκειας του εφέ. Μια αρνητική τιμή καθορίζει την καθυστέρηση σε δευτερόλεπτα. Διαβάστε float.
type: docs
weight: 300
url: /el/aspose.slides.animation/effect/get_delaybetweentextparts/
---
## Effect::get_DelayBetweenTextParts() μέθοδος


Ορίζει μια καθυστέρηση μεταξύ των κινούμενων τμημάτων κειμένου (λέξεων ή γραμμάτων). Μια θετική τιμή καθορίζει το ποσοστό της διάρκειας του εφέ. Μια αρνητική τιμή καθορίζει την καθυστέρηση σε δευτερόλεπτα. Διαβάστε **float**.

```cpp
float Aspose::Slides::Animation::Effect::get_DelayBetweenTextParts() override
```

## Παρατηρήσεις



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Δείτε επίσης

* Κλάση [Effect](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)