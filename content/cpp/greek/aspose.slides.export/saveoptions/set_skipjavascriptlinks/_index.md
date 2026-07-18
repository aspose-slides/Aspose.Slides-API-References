---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει εάν θα παραλείπονται οι υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Γράψτε bool. Η προεπιλεγμένη τιμή είναι false.
type: docs
weight: 118
url: /el/aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) μέθοδος

Καθορίζει εάν θα παραλειφθούν οι υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Γράψτε **bool**. Η προεπιλεγμένη τιμή είναι **false**.

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
```

## Σχόλια

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