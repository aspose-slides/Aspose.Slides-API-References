---
title: set_HandleRepeatedSpaces()
second_title: Aspose.Slides C++ API referencia
description: Megadja, hogyan kell kezelni a Markdown export során az egymás után ismétlődő szabályos szóköz karaktereket.
type: docs
weight: 248
url: /hu/aspose.slides.export/markdownsaveoptions/set_handlerepeatedspaces/
---
## MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces) metódus

Megadja, hogyan kell kezelni a Markdown-export során az egymás után ismétlődő szabályos szóköz karaktereket.

```cpp
void Aspose::Slides::Export::MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces value)
```

## Megjegyzések

Ez a tulajdonság meghatározza, hogy a szomszédos szóközök:
* megőrzik a szabályos szóköz karaktereket,
* váltakoznak a szabályos szóközök és a nem törhető szóköz entitások (**&nbsp;**) között,
* vagy teljesen helyettesítik (az első után) a **&nbsp;** karakterrel, hogy megőrizzék a vizuális igazítást a Markdown-kimenetben.

Az alapértelmezett érték [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/).

## Lásd még

* Enum [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Osztály [MarkdownSaveOptions](../)
* Névterület [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)