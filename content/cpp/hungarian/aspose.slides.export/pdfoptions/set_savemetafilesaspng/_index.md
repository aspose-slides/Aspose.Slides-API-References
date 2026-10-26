---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ API-referencia
description: True a prezentációban használt összes metafájl PNG képekké konvertálásához. Írja bool.
type: docs
weight: 339
url: /hu/aspose.slides.export/pdfoptions/set_savemetafilesaspng/
---
## PdfOptions::set_SaveMetafilesAsPng(bool) metódus

True a prezentációban használt összes metafájl PNG képekké konvertálásához. Írja **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SaveMetafilesAsPng(bool value) override
```

## Megjegyzés

Az alapértelmezett **true**. A Pdf dokumentum tartalmazhat vektorgrafikákat és raszter képeket. Ha a SaveMetafilesAsPng értéke true, akkor a forrás Metafile kép PNG formátumba konvertálódik és raszter képként kerül mentésre a Pdf-be. Ha a SaveMetafilesAsPng értéke false, akkor a forrás Metafile Pdf vektorgrafikává konvertálódik. Mindkét megközelítésnek vannak előnyei és hátrányai. Például, ha a Metafile PNG-re konvertálódik, akkor a létrejövő dokumentum méretezése során minőségromlás fordulhat elő. Ha a Metafile Pdf vektorgrafikává konvertálódik, akkor előfordulhatnak teljesítményproblémák a Pdf megjelenítő eszközben. 

## Lásd még

* Osztály [PdfOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)