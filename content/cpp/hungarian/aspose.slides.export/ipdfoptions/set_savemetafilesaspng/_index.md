---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ API-referencia
description: True, ha a prezentációban használt összes metafájlt PNG képekké konvertálja. Írja bool.
type: docs
weight: 300
url: /hu/aspose.slides.export/ipdfoptions/set_savemetafilesaspng/
---
## IPdfOptions::set_SaveMetafilesAsPng(bool) method


True, ha a prezentációban használt összes metafájlt PNG képekké konvertálja. Írja **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SaveMetafilesAsPng(bool value)=0
```

## Megjegyzés


Alapértelmezett érték **true**. A Pdf dokumentum tartalmazhat vektorgrafikákat és raszteres képeket. Ha a SaveMetafilesAsPng értéke **true**, akkor a forrás Metafile kép Png formátumba konvertálódik, és a Pdf raster képként kerül mentésre. Ha a SaveMetafilesAsPng értéke **false**, akkor a forrás Metafile Pdf vektorgrafikává konvertálódik. Minden megközelítésnek megvannak az előnyei és hátrányai. Például, ha a Metafile PNG formátumba konvertálódik, akkor a dokumentum átméretezésekor minőségveszteség lehetséges. Ha a Metafile Pdf vektorgrafikává konvertálódik, akkor a Pdf megjelenítő eszközben teljesítményproblémák merülhetnek fel. 

## Lásd még

* Osztály [IPdfOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)