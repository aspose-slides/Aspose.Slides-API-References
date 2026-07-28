---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ API hivatkozás
description: True a prezentációban használt összes metafájl PNG képekké konvertálásához. Olvasható bool.
type: docs
weight: 287
url: /hu/aspose.slides.export/ipdfoptions/get_savemetafilesaspng/
---
## IPdfOptions::get_SaveMetafilesAsPng() metódus

True a prezentációban használt összes metafájl PNG képekké konvertálásához. Olvasható **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_SaveMetafilesAsPng()=0
```

## Megjegyzések

Alapértelmezett **true**. A Pdf dokumentum tartalmazhat vektorgrafikákat és raszterképeket. Ha a SaveMetafilesAsPng értéke true, akkor a forrás Metafile kép PNG formátumba konvertálódik, és raszterképként kerül a Pdf-be. Ha a SaveMetafilesAsPng értéke false, akkor a forrás Metafile PDF vektorgrafikává alakul. Mindkét megközelítésnek vannak előnyei és hátrányai. Például, ha a Metafile PNG-re konvertálódik, akkor a végeredmény dokumentum skálázása során minőségvesztés fordulhat elő. Ha a Metafile PDF vektorgrafikává alakul, akkor a PDF megjelenítő eszközökben teljesítményproblémák jelentkezhetnek. 

## Lásd még

* Osztály [IPdfOptions](../)
* Névtere [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)