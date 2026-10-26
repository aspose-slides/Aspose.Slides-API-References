---
title: set_OutputPath()
second_title: Aspose.Slides για την αναφορά API C++
description: "Καθορίζει πού πρέπει να αποθηκευτούν οι εξωτερικοί πόροι. Γράψτε System::String."
type: docs
weight: 92
url: /el/aspose.slides.export/ihtml5options/set_outputpath/
---
## IHtml5Options::set_OutputPath(System::String) μέθοδος

Καθορίζει πού θα πρέπει να αποθηκευτούν οι εξωτερικοί πόροι. Γράψτε [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_OutputPath(System::String value)=0
```

## Σχόλια

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