---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ο χαρακτήρας του τελεστή μεγαλώνει κάθετα ώστε να ταιριάζει με το ύψος του τελεστή του
type: docs
weight: 66
url: /el/aspose.slides.mathtext/imathnaryoperatorproperties/set_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool) μέθοδος


Ο χαρακτήρας του τελεστή μεγαλώνει κάθετα ώστε να ταιριάζει με το ύψος του τελεστή του

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool value)=0
```

## Παρατηρήσεις


Παράδειγμα:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Δείτε επίσης

* Κλάση [IMathNaryOperatorProperties](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)