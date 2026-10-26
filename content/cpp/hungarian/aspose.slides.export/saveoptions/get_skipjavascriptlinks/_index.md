---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides C++ API Referencia
description: Megadja, hogy a prezentáció mentésekor kihagyjuk-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Olvasás bool. Az alapértelmezett érték false.
type: docs
weight: 105
url: /hu/aspose.slides.export/saveoptions/get_skipjavascriptlinks/
---
## SaveOptions::get_SkipJavaScriptLinks() metódus


Megadja, hogy a prezentáció mentésekor kihagyjuk-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Olvasás **bool**. Az alapértelmezett érték **false**.

```cpp
bool Aspose::Slides::Export::SaveOptions::get_SkipJavaScriptLinks() override
```

## Megjegyzés


Ha ez a tulajdonság **true** értékre van állítva, a JavaScript hívásokat tartalmazó hiperhivatkozások mentéskor figyelmen kívül lesznek hagyva.

Ha ez a tulajdonság **false** értékre van állítva, az összes hiperhivatkozás mentésre kerül.

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