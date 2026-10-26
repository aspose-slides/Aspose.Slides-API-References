---
title: get_RefreshThumbnail()
second_title: Aspose.Slides C++ API-referencia
description: Megadja, hogy a prezentáció bélyegképe frissítve lesz-e. Olvasható bool. Az alapértelmezett érték true.
type: docs
weight: 53
url: /hu/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() metódus

Megadja, hogy a prezentáció bélyegképe frissítésre kerül-e. Olvasható **bool**. Az alapértelmezett érték **true**.

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
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

* Osztály [IPptxOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)