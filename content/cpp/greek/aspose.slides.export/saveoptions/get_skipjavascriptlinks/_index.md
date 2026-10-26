---
title: get_SkipJavaScriptLinks()
second_title: Αναφορά API του Aspose.Slides για C++
description: Καθορίζει αν θα παραλειφθούν οι υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Ανάγνωση bool. Η προεπιλεγμένη τιμή είναι false.
type: docs
weight: 105
url: /el/aspose.slides.export/saveoptions/get_skipjavascriptlinks/
---
## SaveOptions::get_SkipJavaScriptLinks() μέθοδος

Προσδιορίζει αν θα παραληφθούν οι υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Ανάγνωση **bool**. Η προεπιλεγμένη τιμή είναι **false**.

```cpp
bool Aspose::Slides::Export::SaveOptions::get_SkipJavaScriptLinks() override
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

* Κλάση [SaveOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)