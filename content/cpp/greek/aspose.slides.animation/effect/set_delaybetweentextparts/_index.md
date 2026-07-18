---
title: set_DelayBetweenTextParts()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει μια καθυστέρηση μεταξύ των αναμεταλλομένων τμημάτων κειμένου (λέξεων ή γραμμάτων). Μια θετική τιμή καθορίζει το ποσοστό της διάρκειας του εφέ. Μια αρνητική τιμή καθορίζει την καθυστέρηση σε δευτερόλεπτα. Γράψτε float.
type: docs
weight: 313
url: /el/aspose.slides.animation/effect/set_delaybetweentextparts/
---
## Effect::set_DelayBetweenTextParts(float) μέθοδος

Καθορίζει μια καθυστέρηση μεταξύ των αναμεταλλομένων τμημάτων κειμένου (λέξεων ή γραμμάτων). Μια θετική τιμή καθορίζει το ποσοστό της διάρκειας του εφέ. Μια αρνητική τιμή καθορίζει την καθυστέρηση σε δευτερόλεπτα. Γράψτε **float**.

```cpp
void Aspose::Slides::Animation::Effect::set_DelayBetweenTextParts(float value) override
```

## Παρατηρήσεις



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Αποκτήστε το πρώτο εφέ της πρώτης διαφάνειας.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Αλλάξτε το τύπο Animate text του εφέ σε "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Ορίστε την καθυστέρηση μεταξύ των αναμεταλλομένων τμημάτων κειμένου στο 20% της διάρκειας του εφέ.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Δείτε επίσης

* Κλάση [Effect](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)