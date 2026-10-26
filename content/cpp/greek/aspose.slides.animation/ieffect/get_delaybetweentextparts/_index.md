---
title: get_DelayBetweenTextParts()
second_title: Αναφορά API του Aspose.Slides για C++
description: Ορίζει καθυστέρηση μεταξύ των κινούμενων τμημάτων κειμένου (λέξεις ή γράμματα). Μία θετική τιμή καθορίζει το ποσοστό διάρκειας του εφέ. Μία αρνητική τιμή καθορίζει την καθυστέρηση σε δευτερόλεπτα. Διαβάζει float.
type: docs
weight: 300
url: /el/aspose.slides.animation/ieffect/get_delaybetweentextparts/
---
## IEffect::get_DelayBetweenTextParts() μέθοδος

Ορίζει καθυστέρηση μεταξύ των κινούμενων τμημάτων κειμένου (λέξεις ή γράμματα). Μία θετική τιμή καθορίζει το ποσοστό διάρκειας του εφέ. Μία αρνητική τιμή καθορίζει την καθυστέρηση σε δευτερόλεπτα. Ανάγνωση **float**.

```cpp
virtual float Aspose::Slides::Animation::IEffect::get_DelayBetweenTextParts()=0
```

## Σχόλια



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Λάβετε το πρώτο εφέ της πρώτης διαφάνειας.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Αλλαγή του τύπου AnimateText του εφέ σε "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Ορίστε την καθυστέρηση μεταξύ των κινούμενων τμημάτων κειμένου στο 20% της διάρκειας του εφέ.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Δείτε επίσης

* Κλάση [IEffect](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)