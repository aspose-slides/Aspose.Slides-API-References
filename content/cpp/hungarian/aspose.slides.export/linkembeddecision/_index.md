---
title: LinkEmbedDecision
second_title: Aspose.Slides C++ API referencia
description: Meghatározza, hogyan lesz feldolgozva az objektum mentés közben.
type: docs
weight: 911
url: /hu/aspose.slides.export/linkembeddecision/
---
## LinkEmbedDecision enum

Meghatározza, hogyan lesz feldolgozva az objektum mentés közben.

```cpp
enum class LinkEmbedDecision
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| Link | 0 | Az objektum külsőként lesz tárolva, URL-re hivatkozva |
| Embed | 1 | Az objektumot be kell ágyazni egy generált fájlba, ha lehetséges. Ha a beágyazás lehetetlen, a GetUrl lesz meghívva, és az eredménytől függően az objektum URL-re hivatkozik vagy figyelmen kívül van hagyva. |
| Ignore | 2 | Az objektum figyelmen kívül marad. |

## Lásd még

* Névtér [Aspose::Slides::Export](../)
* Könyvtár [Aspose.Slides](../../)