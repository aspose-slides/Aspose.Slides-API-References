---
title: get_DelimiterShape()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Καθορίζει το σχήμα των διαχωριστών στο αντικείμενο διαχωριστή. Όταν είναι MathDelimiterShape::Centered, οι διαχωριστές κεντράρονται γύρω από τον άξονα των μαθηματικών κειμένων και προσαρμόζονται ώστε να καλύψουν ολόκληρο το ύψος του περιεχομένου τους. Όταν είναι MathDelimiterShape::Match, το ύψος και το σχήμα τους τροποποιούνται ώστε να ταιριάζουν ακριβώς με το περιεχόμενό τους."
type: docs
weight: 118
url: /el/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## IMathDelimiter::get_DelimiterShape() μέθοδος


Καθορίζει το σχήμα των διαχωριστών στο αντικείμενο διαχωριστή. Όταν είναι [MathDelimiterShape::Centered](../../mathdelimitershape/), οι διαχωριστές κεντράρονται γύρω από τον άξονα των μαθηματικών κειμένων και προσαρμόζονται ώστε να καλύπτουν ολόκληρο το ύψος του περιεχομένου τους. Όταν είναι [MathDelimiterShape::Match](../../mathdelimitershape/), το ύψος και το σχήμα τους τροποποιούνται ώστε να ταιριάζουν ακριβώς με το περιεχόμενό τους.

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Δείτε επίσης

* Απαρίθμηση [MathDelimiterShape](../../mathdelimitershape/)
* Κλάση [IMathDelimiter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)