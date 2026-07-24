---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, ob beim Speichern der Präsentation Hyperlinks mit JavaScript-Aufrufen übersprungen werden sollen. Schreiben bool. Der Standardwert ist false.
type: docs
weight: 118
url: /de/aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) Methode

Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Schreiben **bool**. Der Standardwert ist **false**.

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
```

## Hinweis

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

* Klasse [SaveOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)