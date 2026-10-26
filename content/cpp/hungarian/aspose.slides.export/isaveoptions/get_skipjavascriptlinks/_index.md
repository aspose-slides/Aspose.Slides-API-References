---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides for C++ API referenciája
description: Megadja, hogy a bemutató mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Olvasás bool. Az alapértelmezett érték false.
type: docs
weight: 105
url: /hu/aspose.slides.export/isaveoptions/get_skipjavascriptlinks/
---
## ISaveOptions::get_SkipJavaScriptLinks() metódus


Megadja, hogy a bemutató mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Olvasás **bool**. Az alapértelmezett érték **false**.

```cpp
virtual bool Aspose::Slides::Export::ISaveOptions::get_SkipJavaScriptLinks()=0
```

## Megjegyzések


Ha ez a tulajdonság **true** értékre van állítva, a JavaScript hívásokat tartalmazó hiperhivatkozások mentéskor figyelmen kívül lesznek hagyva.

Ha ez a tulajdonság **false** értékre van állítva, az összes hiperhivatkozás el lesz mentve.

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Lásd még

* Osztály [ISaveOptions](../)
* Névterület [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)