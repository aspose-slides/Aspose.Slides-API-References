---
title: get_RefreshThumbnail()
second_title: Aspose.Slides C++ API Referenciája
description: Megadja, hogy a prezentáció bélyegképe frissül-e. Olvasható bool. Alapértelmezett érték true.
type: docs
weight: 53
url: /hu/aspose.slides.export/pptxoptions/get_refreshthumbnail/
---
## PptxOptions::get_RefreshThumbnail() metódus


Megadja, hogy a prezentáció bélyegképe frissül-e. Olvasható **bool**. Alapértelmezett érték **true**.

```cpp
bool Aspose::Slides::Export::PptxOptions::get_RefreshThumbnail() override
```

## Megjegyzések


Ha az opció értéke **true**, az új bélyegkép lesz előállítva.

Ha az opció értéke **false**, a jelenlegi bélyegkép változatlanul mentésre kerül.

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Lásd még

* Osztály [PptxOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)