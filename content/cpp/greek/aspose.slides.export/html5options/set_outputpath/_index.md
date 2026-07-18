---
title: set_OutputPath()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Καθορίζει πού πρέπει να αποθηκευτούν οι εξωτερικοί πόροι. Γράψτε System::String."
type: docs
weight: 92
url: /el/aspose.slides.export/html5options/set_outputpath/
---
## Html5Options::set_OutputPath(System::String) μέθοδος


Καθορίζει πού πρέπει να αποθηκευτούν οι εξωτερικοί πόροι. Γράψτε [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Export::Html5Options::set_OutputPath(System::String value) override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [Html5Options](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)