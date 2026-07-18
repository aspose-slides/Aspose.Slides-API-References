---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides για C++ API
description: Καθορίζει αν θα παραλειφθούν οι υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Διαβάστε bool. Η προεπιλεγμένη τιμή είναι false.
type: docs
weight: 105
url: /el/aspose.slides.export/isaveoptions/get_skipjavascriptlinks/
---
## ISaveOptions::get_SkipJavaScriptLinks() μέθοδος


Καθορίζει αν θα παραλειφθούν οι υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Διαβάστε **bool**. Η προεπιλεγμένη τιμή είναι **false**.

```cpp
virtual bool Aspose::Slides::Export::ISaveOptions::get_SkipJavaScriptLinks()=0
```

## Παρατηρήσεις


Όταν αυτή η ιδιότητα οριστεί σε **true**, οι υπερσυνδέσεις με κλήσεις JavaScript θα αγνοηθούν κατά την αποθήκευση.

Όταν αυτή η ιδιότητα οριστεί σε **false**, όλες οι υπερσυνδέσεις θα αποθηκευτούν.

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
* Library [Aspose.Slides](../../../)