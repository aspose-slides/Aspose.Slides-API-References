---
title: MathLimit()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αρχικοποιεί μια νέα παρουσία της κλάσης MathLimit.
type: docs
weight: 53
url: /el/aspose.slides.mathtext/mathlimit/mathlimit/
---
## MathLimit::MathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) κατασκευαστής


Αρχικοποιεί μια νέα παρουσία της κλάσης [MathLimit](../).

```cpp
Aspose::Slides::MathText::MathLimit::MathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"\U0001d45b→∞"), false);
```

## MathLimit::MathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) κατασκευαστής


Αρχικοποιεί μια νέα παρουσία της κλάσης [MathLimit](../) με κατώτερο όριο

```cpp
Aspose::Slides::MathText::MathLimit::MathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"\U0001d45b→∞"));
```

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathLimit](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)