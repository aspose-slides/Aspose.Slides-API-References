---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides C++ API referencia
description: Igaz, ha az összes prezentációban használt metafájlt PNG képekké konvertálja. Bool típusú érték.
type: docs
weight: 326
url: /hu/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() metódus


Igaz, ha az összes prezentációban használt metafájl PNG képekké konvertálódik. Olvasható **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## Megjegyzések


Az alapértelmezett érték **true**. A Pdf dokumentum tartalmazhat vektoros grafikákat és raszter képeket. Ha a SaveMetafilesAsPng értéke **true**, akkor a forrás Metafile kép Png formátumba konvertálódik, és raszter képként lesz elmentve a Pdf-be. Ha a SaveMetafilesAsPng értéke **false**, akkor a forrás Metafile Pdf vektoros grafikává konvertálódik. Mindkét megközelítésnek vannak előnyei és hátrányai. Például, ha a Metafile PNG-re konvertálódik, akkor a dokumentum méretezése során előfordulhat bizonyos minőségveszteség. Ha a Metafile Pdf vektoros grafikává konvertálódik, akkor előfordulhatnak teljesítményproblémák a Pdf megjelenítő eszközben. 
## Lásd még

* Osztály [PdfOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)