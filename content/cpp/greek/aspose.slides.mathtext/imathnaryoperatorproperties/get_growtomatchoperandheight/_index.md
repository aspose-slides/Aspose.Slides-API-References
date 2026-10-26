---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ο χαρακτήρας του τελεστή μεγαλώνει κάθετα ώστε να ταιριάζει με το ύψος του τελεστέου
type: docs
weight: 53
url: /el/aspose.slides.mathtext/imathnaryoperatorproperties/get_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::get_GrowToMatchOperandHeight() μέθοδος

Ο χαρακτήρας του τελεστή μεγαλώνει κάθετα ώστε να ταιριάζει με το ύψος του τελεστέου

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_GrowToMatchOperandHeight()=0
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
* Library [Aspose.Slides](../../../)