---
title: get_EmbedImages()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει την επιλογή ενσωμάτωσης εικόνων. Διαβάζει bool.
type: docs
weight: 53
url: /el/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() μέθοδος


Επιστρέφει την επιλογή ενσωμάτωσης εικόνων. Διαβάζει **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
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

* Κλάση [Html5Options](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)