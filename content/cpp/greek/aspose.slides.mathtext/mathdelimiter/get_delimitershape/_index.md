---
title: get_DelimiterShape()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Καθορίζει το σχήμα των οριοθετών στο αντικείμενο delimiter. Όταν είναι MathDelimiterShape::Centered, οι οριοθέτες κεντράρονται γύρω από τον μαθηματικό άξονα του μαθηματικού κειμένου και προσαρμόζονται ώστε να ταιριάζουν στο πλήρες ύψος του περιεχομένου τους. Όταν είναι MathDelimiterShape::Match, το ύψος και το σχήμα τους τροποποιούνται ώστε να ταιριάζουν ακριβώς στο περιεχόμενό τους."
type: docs
weight: 118
url: /el/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() μέθοδος

Καθορίζει το σχήμα των οριοθέσεων στο αντικείμενο delimiter. Όταν είναι [MathDelimiterShape::Centered](../../mathdelimitershape/), οι οριοθέσεις κεντράρονται γύρω από τον μαθηματικό άξονα του μαθηματικού κειμένου και εξακολουθούν να προσαρμόζονται ώστε να ταιριάζουν στο πλήρες ύψος του περιεχομένου τους. Όταν είναι [MathDelimiterShape::Match](../../mathdelimitershape/), το ύψος και το σχήμα τους τροποποιούνται ώστε να ταιριάζουν ακριβώς στο περιεχόμενό τους.

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Δείτε επίσης

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)