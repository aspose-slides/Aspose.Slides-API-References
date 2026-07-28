---
title: EmbeddingLevel
second_title: Aspose.Slides C++ API Referencia
description: Képviseli a betűkészlet beágyazásához kapcsolódó licencjogokat.
type: docs
weight: 5786
url: /hu/aspose.slides/embeddinglevel/
---
## EmbeddingLevel enum

Képviseli a betűkészlet beágyazására vonatkozó licencjogokat.

```cpp
enum class EmbeddingLevel : uint16_t
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| Installable | 0 | [Fonts](../fonts/) ezzel a beállítással jelzi, hogy beágyazhatók és véglegesen telepíthetők a távoli rendszeren egy alkalmazás által. A távoli rendszer felhasználója azonos jogokat, kötelezettségeket és licenceket kap a betűkészletre, mint a betűkészlet eredeti vásárlója, és ugyanazon végfelhasználói licencszerződés, szerzői jog, formatervezési szabadalom és/vagy védjegy hatálya alá esik, mint az eredeti vásárló. |
| Restricted | 2 | [Fonts](../fonts/) amelyeknél csak ez a bit van beállítva, nem módosíthatók, beágyazhatók vagy cserélhetők semmilyen módon, amíg a jogi tulajdonos engedélyét meg nem szerzik. |
| PreviewPrint | 4 | Ha ez a bit be van állítva, a betűkészlet beágyazható, és ideiglenesen betölthető a távoli rendszeren. Az \"Preview & Print\" betűkészleteket tartalmazó dokumentumok csak \"read-only;\" módban nyithatók meg; a dokumentumot nem lehet módosítani. |
| Editable | 8 | Ha ez a bit be van állítva, a betűkészlet beágyazható, de csak ideiglenesen telepíthető más rendszereken. A \"Preview & Print\" betűkészletekkel ellentétben, az \"Editable\" betűkészleteket tartalmazó dokumentumok megnyithatók olvasásra, a szerkesztés engedélyezett, és a módosítások menthetők. |
| NoSubsetting | 256 | Ha ez a bit be van állítva, a betűkészlet nem szubszetizálható a beágyazás előtt. A bitek 0-3 és 9-ben megadott egyéb beágyazási korlátozások is alkalmazandók. |
| BitmapOnly | 512 | Ha ez a bit be van állítva, csak a betűkészletben található bitmap képek ágyazhatók be. Outline adatok nem ágyazhatók be. Ha a betűkészletben nincs elérhető bitmap, akkor a betűkészletet beágyazhatatlannak tekintik, és a beágyazási szolgáltatások hibával végződnek. |

## Lásd még

* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)