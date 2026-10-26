---
title: SplitTextByColumns()
second_title: Aspose.Slides για C++ API Αναφορά
description: Διαιρεί το κειμενικό περιεχόμενο του ITextFrame σε έναν πίνακα συμβολοσειρών, όπου κάθε στοιχείο αντιστοιχεί σε μια ξεχωριστή στήλη κειμένου μέσα στο πλαίσιο.
type: docs
weight: 118
url: /el/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() μέθοδος


Διαιρεί το κειμενικό περιεχόμενο του [ITextFrame](../) σε έναν πίνακα συμβολοσειρών, 

 όπου κάθε στοιχείο αντιστοιχεί σε μια ξεχωριστή στήλη κειμένου μέσα στο πλαίσιο.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```


### Τιμή Επιστροφής

Ένας πίνακας συμβολοσειρών, όπου κάθε συμβολοσειρά αντιπροσωπεύει το κειμενικό περιεχόμενο μιας συγκεκριμένης στήλης 

 στο [ITextFrame](../).

## Σχόλια



Εάν το πλαίσιο κειμένου δεν περιέχει πολλαπλές στήλες, ο επιστρεφόμενος πίνακας θα έχει ένα μόνο στοιχείο 

 που περιέχει ολόκληρο το κείμενο. 

Οι κενές στήλες θα απεικονίζονται ως κενές συμβολοσειρές στον πίνακα. 

Το παρακάτω παράδειγμα δείχνει πώς να χρησιμοποιήσετε το [ITextFrame::SplitTextByColumns](./): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Λάβετε το πρώτο σχήμα στη διαφάνεια και μετατρέψτε το σε ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Διαιρέστε το περιεχόμενο του πλαισίου κειμένου σε στήλες
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Εκτυπώστε το κείμενο κάθε στήλης στην κονσόλα
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Δείτε επίσης

* Τύπος [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [ITextFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)