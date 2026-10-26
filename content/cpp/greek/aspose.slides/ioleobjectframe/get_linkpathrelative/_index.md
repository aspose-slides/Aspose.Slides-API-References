---
title: get_LinkPathRelative()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Επιστρέφει τη σχετική διαδρομή σε ένα συνδεδεμένο αρχείο εφόσον υπάρχει· διαφορετικά επιστρέφει μια κενή συμβολοσειρά. Μόνο ανάγνωση System::String."
type: docs
weight: 118
url: /el/aspose.slides/ioleobjectframe/get_linkpathrelative/
---
## IOleObjectFrame::get_LinkPathRelative() μέθοδος

Επιστρέφει τη σχετική διαδρομή σε ένα συνδεδεμένο αρχείο αν υπάρχει, διαφορετικά επιστρέφει μια κενή συμβολοσειρά. Μόνο ανάγνωση [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::IOleObjectFrame::get_LinkPathRelative()=0
```

## Παρατηρήσεις

Στις παρουσιάσεις Ppt, ορισμένοι σύνδεσμοι αντικειμένων Ole ενδέχεται να έχουν σχετική αναπαράσταση.

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
* Κλάση [IOleObjectFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)