---
title: SplitTextByColumns()
second_title: Aspose.Slides για C++ Αναφορά API
description: Διαιρεί το περιεχόμενο κειμένου του ITextFrame σε μια σειρά από συμβολοσειρές, όπου κάθε στοιχείο αντιστοιχεί σε μια ξεχωριστή στήλη κειμένου μέσα στο πλαίσιο.
type: docs
weight: 144
url: /el/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() μέθοδος


Διαίρει το κείμενο του [ITextFrame](../../itextframe/) σε μια σειρά από συμβολοσειρές, 
 όπου κάθε στοιχείο αντιστοιχεί σε μια ξεχωριστή στήλη κειμένου μέσα στο πλαίσιο.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```

### Τιμή Επιστροφής

Μία σειρά από συμβολοσειρές, όπου κάθε συμβολοσειρά αντιπροσωπεύει το κείμενο μιας συγκεκριμένης στήλης 
 στο [ITextFrame](../../itextframe/).

## Παρατηρήσεις



Εάν το πλαίσιο κειμένου δεν περιέχει πολλαπλές στήλες, η επιστρεφόμενη σειρά θα έχει ένα μόνο στοιχείο 
 που περιλαμβάνει ολόκληρο το κείμενο. 

 Οι κενές στήλες θα εμφανίζονται ως κενές συμβολοσειρές στη σειρά. 

Το παρακάτω παράδειγμα δείχνει πώς να χρησιμοποιήσετε το [TextFrame::SplitTextByColumns](./): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Get the first shape on the slide and cast it to ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Split the text frame content into columns
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Print each column's text to the console
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [TextFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)