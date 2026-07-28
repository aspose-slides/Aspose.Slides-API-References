---
title: get_ParagraphFormat()
second_title: Aspose.Slides C++ API-referencia
description: Visszaadja a formázási objektumot ehhez a bekezdéshez. Csak olvasható IParagraphFormat.
type: docs
weight: 14
url: /hu/aspose.slides/paragraph/get_paragraphformat/
---
## Paragraph::get_ParagraphFormat() metódus


Visszaadja a formázási objektumot ehhez a bekezdéshez. Csak olvasható [IParagraphFormat](../../iparagraphformat/).

```cpp
System::SharedPtr<IParagraphFormat> Aspose::Slides::Paragraph::get_ParagraphFormat() override
```

## Megjegyzés


A formázási objektum csak a jelenlegi bekezdéshez definiált formázási paramétereket tartalmaz, az örökölt adatok nem kerülnek alkalmazásra.

Az örökölt értékeket is tartalmazó hatásos értékek lekéréséhez használja a [ParagraphFormat::GetEffective](../../paragraphformat/geteffective/) metódust.
## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IParagraphFormat](../../iparagraphformat/)
* Osztály [Paragraph](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)