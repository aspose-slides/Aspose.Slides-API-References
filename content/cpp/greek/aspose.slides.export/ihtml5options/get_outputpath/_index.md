---
title: get_OutputPath()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Καθορίζει πού πρέπει να αποθηκευτούν οι εξωτερικοί πόροι. Διαβάστε System::String."
type: docs
weight: 79
url: /el/aspose.slides.export/ihtml5options/get_outputpath/
---
## IHtml5Options::get_OutputPath() μέθοδος


Καθορίζει πού πρέπει να αποθηκευτούν οι εξωτερικοί πόροι. Διαβάστε [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::IHtml5Options::get_OutputPath()=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [IHtml5Options](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)