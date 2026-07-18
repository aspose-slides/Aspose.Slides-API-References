---
title: set_EmbedImages()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ορίζει την επιλογή ενσωμάτωσης εικόνων. Γράψτε bool.
type: docs
weight: 66
url: /el/aspose.slides.export/ihtml5options/set_embedimages/
---
## IHtml5Options::set_EmbedImages(bool) μέθοδος


Ορίζει την επιλογή ενσωμάτωσης εικόνων. Γράψτε **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_EmbedImages(bool value)=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Δείτε επίσης

* Κλάση [IHtml5Options](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)