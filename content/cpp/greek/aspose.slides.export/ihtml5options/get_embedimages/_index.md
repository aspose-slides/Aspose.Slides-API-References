---
title: get_EmbedImages()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει την επιλογή ενσωμάτωσης εικόνων. Ανάγνωση bool.
type: docs
weight: 53
url: /el/aspose.slides.export/ihtml5options/get_embedimages/
---
## IHtml5Options::get_EmbedImages() μέθοδος


Επιστρέφει την επιλογή ενσωμάτωσης εικόνων. Ανάγνωση **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_EmbedImages()=0
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