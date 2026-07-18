---
title: set_DelimiterShape()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Καθορίζει το σχήμα των οριοθετών στο αντικείμενο delimiter. Όταν είναι MathDelimiterShape::Centered, οι οριοθέτες κεντράρονται γύρω από τον μαθηματικό άξονα του μαθηματικού κειμένου και εξακολουθούν να προσαρμόζονται ώστε να ταιριάζουν με ολόκληρο το ύψος του περιεχομένου τους. Όταν είναι MathDelimiterShape::Match, το ύψος και το σχήμα τους τροποποιούνται ώστε να ταιριάζουν ακριβώς με το περιεχόμενό τους."
type: docs
weight: 131
url: /el/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape(MathDelimiterShape) μέθοδος


Καθορίζει το σχήμα των οριοθετήρων στο αντικείμενο delimiter. Όταν είναι [MathDelimiterShape::Centered](../../mathdelimitershape/), οι οριοθέτες κεντράρονται γύρω από τον μαθηματικό άξονα του μαθηματικού κειμένου και εξακολουθούν να προσαρμόζονται ώστε να ταιριάζουν με ολόκληρο το ύψος του περιεχομένου τους. Όταν είναι [MathDelimiterShape::Match](../../mathdelimitershape/), το ύψος και το σχήμα τους τροποποιούνται ώστε να ταιριάζουν ακριβώς με το περιεχόμενό τους.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Δείτε επίσης

* Απαρίθμηση [MathDelimiterShape](../../mathdelimitershape/)
* Κλάση [MathDelimiter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)