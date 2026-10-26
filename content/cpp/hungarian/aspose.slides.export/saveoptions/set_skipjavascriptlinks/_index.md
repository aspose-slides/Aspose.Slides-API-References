---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides C++ API referencia
description: Megadja, hogy a prezentáció mentésekor ki kell-e hagyni a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Írja bool. Az alapértelmezett érték false.
type: docs
weight: 118
url: /hu/aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) metódus

Megadja, hogy a prezentáció mentésekor ki kell-e hagyni a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Írja **bool**. Az alapértelmezett érték **false**.

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
```

## Megjegyzés

Ha ez a tulajdonság **true** értékre van állítva, a JavaScript hívásokat tartalmazó hiperhivatkozások mentéskor figyelmen kívül lesznek hagyva.

Ha ez a tulajdonság **false** értékre van állítva, minden hiperhivatkozás mentésre kerül.

Példa:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Lásd még

* Osztály [SaveOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)