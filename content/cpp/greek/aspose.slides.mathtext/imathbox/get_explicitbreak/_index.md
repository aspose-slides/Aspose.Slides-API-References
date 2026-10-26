---
title: get_ExplicitBreak()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Καθορίζει εάν υπάρχει αλλαγή γραμμής στην αρχή του αντικειμένου Box, έτσι ώστε η γραμμή να τυλίγεται στην αρχή του αντικειμένου Box. Καθορίζει τον αριθμό του τελεστή στη προηγούμενη γραμμή μαθηματικού κειμένου που θα χρησιμοποιηθεί ως σημείο ευθυγράμμισης για την τρέχουσα γραμμή μαθηματικού κειμένου. δυνατές τιμές: 1..255 Προεπιλογή: 0 (χωρίς explicit break)"
type: docs
weight: 118
url: /el/aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() μέθοδος


Το Explicit break καθορίζει εάν υπάρχει αλλαγή γραμμής στην αρχή του αντικειμένου Box, ώστε η γραμμή να τυλίγεται στην αρχή του αντικειμένου Box. Καθορίζει τον αριθμό του τελεστή στη προηγούμενη γραμμή μαθηματικού κειμένου που θα χρησιμοποιηθεί ως σημείο ευθυγράμμισης για την τρέχουσα γραμμή μαθηματικού κειμένου. Πιθανές τιμές: 1..255 Προεπιλογή: 0 (no explicit break)

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Δείτε επίσης

* Κλάση [IMathBox](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)