---
title: set_RefreshThumbnail()
second_title: Aspose.Slides C++ API referencia
description: Megadja, hogy a bemutató bélyegképe frissítve lesz-e. Írja bool. Alapértelmezett érték true.
type: docs
weight: 66
url: /hu/aspose.slides.export/ipptxoptions/set_refreshthumbnail/
---
## IPptxOptions::set_RefreshThumbnail(bool) metódus


Megadja, hogy a bemutató bélyegképét frissíteni kell-e. Írja **bool**. Az alapértelmezett érték **true**.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_RefreshThumbnail(bool value)=0
```

## Megjegyzések


Ha a beállítás értéke **true**, az új bélyegkép lesz generálva.

Ha a beállítás értéke **false**, a jelenlegi bélyegkép változatlanul lesz mentve.

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Lásd még

* Osztály [IPptxOptions](../)
* Névterület [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)