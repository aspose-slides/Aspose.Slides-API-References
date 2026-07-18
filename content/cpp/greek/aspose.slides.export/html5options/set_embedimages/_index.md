---
title: set_EmbedImages()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ορίζει την επιλογή ενσωμάτωσης εικόνων. Γράψτε bool.
type: docs
weight: 66
url: /el/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) μέθοδος


Ορίζει την επιλογή ενσωμάτωσης εικόνων. Γράψτε **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
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