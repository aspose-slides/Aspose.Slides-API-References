---
title: set_RefreshThumbnail()
second_title: Aspose.Slides C++ API referencia
description: Megadja, hogy a prezentáció bélyegképe frissítve lesz-e. Írja bool. Alapértelmezett érték true.
type: docs
weight: 66
url: /hu/aspose.slides.export/pptxoptions/set_refreshthumbnail/
---
## PptxOptions::set_RefreshThumbnail(bool) módszer


Megadja, hogy a prezentáció bélyegképe frissítve lesz-e. Írja **bool**. Alapértelmezett érték **true**.

```cpp
void Aspose::Slides::Export::PptxOptions::set_RefreshThumbnail(bool value) override
```

## Megjegyzések


Ha a beállítás értéke **true**, az új bélyegkép lesz generálva.

Ha a beállítás értéke **false**, a jelenlegi bélyegkép változatlanul mentésre kerül.

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Lásd még

* Osztály [PptxOptions](../)
* Névterület [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)