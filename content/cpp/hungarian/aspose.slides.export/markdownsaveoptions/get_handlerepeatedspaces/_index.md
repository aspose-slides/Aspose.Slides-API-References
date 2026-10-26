---
title: get_HandleRepeatedSpaces()
second_title: Aspose.Slides C++ API referencia
description: Megadja, hogyan kell kezelni a többszörös szabályos szóköz karaktereket a Markdown exportálás során.
type: docs
weight: 235
url: /hu/aspose.slides.export/markdownsaveoptions/get_handlerepeatedspaces/
---
## MarkdownSaveOptions::get_HandleRepeatedSpaces() const metódus

Megadja, hogyan kell kezelni a többszörös szabályos szóköz karaktereket a Markdown exportálás során.

```cpp
Aspose::Slides::Export::HandleRepeatedSpaces Aspose::Slides::Export::MarkdownSaveOptions::get_HandleRepeatedSpaces() const
```

## Megjegyzések

Ez a tulajdonság meghatározza, hogy az egymást követő szóközök * megmaradnak-e szabályos szóköz karakterként,
* felváltva jelennek meg szabályos szóközök és nem törő szóköz entitások (**&nbsp;**) között,
* vagy teljesen helyettesítve vannak (az első után) **&nbsp;**-vel, hogy megőrizzék a vizuális igazítást a Markdown kimenetben.

Az alapértelmezett érték [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## Lásd még

* Enumeráció [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Osztály [MarkdownSaveOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)