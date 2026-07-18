---
title: set_DelimiterShape()
second_title: Αναφορά API του Aspose.Slides για C++
description: "Καθορίζει το σχήμα των οριοσημασιών στο αντικείμενο delimiter. Όταν είναι MathDelimiterShape::Centered, τα οριοσήματα τοποθετούνται κεντραρισμένα γύρω από τον μαθηματικό άξονα του μαθηματικού κειμένου και εξακολουθούν να προσαρμόζονται ώστε να ταιριάζουν στο συνολικό ύψος του περιεχομένου τους. Όταν είναι MathDelimiterShape::Match, το ύψος και το σχήμα τους τροποποιούνται ώστε να ταιριάζουν ακριβώς με το περιεχόμενό τους."
type: docs
weight: 131
url: /el/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) μέθοδος


Καθορίζει το σχήμα των οριοσημασιών στο αντικείμενο delimiter. Όταν είναι [MathDelimiterShape::Centered](../../mathdelimitershape/), τα οριοσήματα ευθυγραμμίζονται γύρω από τον μαθηματικό άξονα του μαθηματικού κειμένου και εξακολουθούν να προσαρμόζονται ώστε να ταιριάζουν στο συνολικό ύψος του περιεχομένου τους. Όταν είναι [MathDelimiterShape::Match](../../mathdelimitershape/), το ύψος και το σχήμα τους τροποποιούνται ώστε να ταιριάζουν ακριβώς με το περιεχόμενό τους.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
```

## Σχόλια


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