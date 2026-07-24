---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Lesen bool. Der Standardwert ist false.
type: docs
weight: 105
url: /de/aspose.slides.export/isaveoptions/get_skipjavascriptlinks/
---
## ISaveOptions::get_SkipJavaScriptLinks() Methode

Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Lesen **bool**. Der Standardwert ist **false**.

```cpp
virtual bool Aspose::Slides::Export::ISaveOptions::get_SkipJavaScriptLinks()=0
```

## Hinweise

Wenn diese Eigenschaft auf **true** gesetzt ist, werden Hyperlinks mit JavaScript-Aufrufen beim Speichern ignoriert.

Wenn diese Eigenschaft auf **false** gesetzt ist, werden alle Hyperlinks gespeichert.

Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Siehe auch

* Klasse [ISaveOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)