---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides C++ API referencia
description: Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Írható bool. Az alapértelmezett érték false.
type: docs
weight: 118
url: /hu/aspose.slides.export/isaveoptions/set_skipjavascriptlinks/
---
## ISaveOptions::set_SkipJavaScriptLinks(bool) metódus

Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Írható **bool**. Az alapértelmezett érték **false**.

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_SkipJavaScriptLinks(bool value)=0
```

## Megjegyzések

Ha ez a tulajdonság **true** értékre van állítva, a JavaScript hívásokat tartalmazó hiperhivatkozások a mentés során figyelmen kívül lesznek hagyva.

Ha ez a tulajdonság **false** értékre van állítva, minden hiperhivatkozás mentésre kerül.

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Lásd még

* Osztály [ISaveOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)