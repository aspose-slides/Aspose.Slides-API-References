---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Καθορίζει αν θα παραλειφθούν οι υπερσύνδεσμοι με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Γράψτε bool. Η προεπιλεγμένη τιμή είναι false.
type: docs
weight: 118
url: /el/aspose.slides.export/isaveoptions/set_skipjavascriptlinks/
---
## ISaveOptions::set_SkipJavaScriptLinks(bool) μέθοδος


Καθορίζει αν θα παραλειφθούν οι υπερσύνδεσμοι με κλήσεις JavaScript κατά τη αποθήκευση της παρουσίασης. Γράψτε **bool**. Η προεπιλεγμένη τιμή είναι **false**.

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_SkipJavaScriptLinks(bool value)=0
```

## Παρατηρήσεις


Όταν αυτή η ιδιότητα οριστεί σε **true**, οι υπερσύνδεσμοι με κλήσεις JavaScript θα αγνοηθούν κατά την αποθήκευση.

Όταν αυτή η ιδιότητα οριστεί σε **false**, όλοι οι υπερσύνδεσμοι θα αποθηκευτούν.

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Δείτε επίσης

* Κλάση [ISaveOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)