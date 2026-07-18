---
title: get_LinkPathRelative()
second_title: Αναφορά API Aspose.Slides για C++
description: "Επιστρέφει τη σχετική διαδρομή σε ένα συνδεδεμένο αρχείο εάν υπάρχει· διαφορετικά επιστρέφει κενή συμβολοσειρά. Μόνο για ανάγνωση System::String."
type: docs
weight: 131
url: /el/aspose.slides/oleobjectframe/get_linkpathrelative/
---
## OleObjectFrame::get_LinkPathRelative() μέθοδος

Επιστρέφει τη σχετική διαδρομή σε ένα συνδεδεμένο αρχείο, εάν υπάρχει· διαφορετικά επιστρέφει κενή συμβολοσειρά. Μόνο για ανάγνωση [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::OleObjectFrame::get_LinkPathRelative() override
```

## Παρατηρήσεις

Στις παρουσιάσεις Ppt, ορισμένοι σύνδεσμοι αντικειμένων Ole μπορεί να έχουν σχετική αναπαράσταση.

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [OleObjectFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)