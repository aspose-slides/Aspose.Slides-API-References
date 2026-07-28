---
title: PdfAccessPermissions
second_title: Aspose.Slides C++ API referencia
description: Tartalmaz egy jelzőkészletet, amely meghatározza, hogy a dokumentum felhasználói hozzáféréssel történő megnyitásakor milyen hozzáférési engedélyeket kell biztosítani.
type: docs
weight: 989
url: /hu/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enum

Megadja, hogy a felhasználó mely hozzáférési engedélyeket kapja, amikor a dokumentumot felhasználói hozzáféréssel nyitják meg.

```cpp
enum class PdfAccessPermissions
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| None | 0 | Megadja, hogy a felhasználónak nincs hozzáférési jogosultsága. |
| PrintDocument | 4 | Megadja, hogy a felhasználó nyomtathatja-e a dokumentumot (esetleg nem a legmagasabb minőségi szinten, attól függően, hogy a(z) [PdfAccessPermissions::HighQualityPrint](./) bit is be van-e állítva). |
| ModifyContent | 8 | Megadja, hogy a felhasználó módosíthatja-e a dokumentum tartalmát olyan műveletekkel, amelyek nem a(z) [PdfAccessPermissions::AddOrModifyFields](./), [PdfAccessPermissions::FillExistingFields](./), [PdfAccessPermissions::AssembleDocument](./) bitekkel szabályozottak. |
| CopyTextAndGraphics | 16 | Megadja, hogy a felhasználó másolhat-e vagy egyéb módon kinyerheti a szöveget és a grafikákat a dokumentumból olyan műveletekkel, amelyek nem a(z) [PdfAccessPermissions::ExtractTextAndGraphics](./) bit által szabályozottak. |
| AddOrModifyFields | 32 | Megadja, hogy a felhasználó hozzáadhat-e vagy módosíthat-e szöveges megjegyzéseket, kitöltheti-e az interaktív űrlapmezőket, és ha a(z) [PdfAccessPermissions::ModifyContent](./) bit is be van állítva, létrehozhat vagy módosíthat interaktív űrlapmezőket (beleértve az aláírásmezőket is). |
| FillExistingFields | 256 | Megadja, hogy a felhasználó kitöltheti-e a már létező interaktív űrlapmezőket (beleértve az aláírásmezőket is), még akkor is, ha a(z) [PdfAccessPermissions::AddOrModifyFields](./) bit ki van kapcsolva. |
| ExtractTextAndGraphics | 512 | Megadja, hogy a felhasználó kinyerheti-e a szöveget és a grafikákat a fogyatékkal élő felhasználók hozzáférhetőségének támogatására vagy más célokra. |
| AssembleDocument | 1024 | Megadja, hogy a felhasználó összeállíthatja-e a dokumentumot (oldalak beszúrása, forgatása vagy törlése, valamint könyvjelzők vagy miniképek létrehozása), még akkor is, ha a(z) [PdfAccessPermissions::ModifyContent](./) bit ki van kapcsolva. |
| HighQualityPrint | 2048 | Megadja, hogy a felhasználó nyomtathatja-e a dokumentumot olyan reprezentációra, amelyből a PDF tartalom hű digitális másolata előállítható. Ha ez a bit ki van kapcsolva (és a(z) [PdfAccessPermissions::PrintDocument](./) bit be van állítva), a nyomtatás csak alacsony szintű megjelenítési formára korlátozódik, amely esetleg alacsonyabb minőségű. |

## Lásd még

* Névtér [Aspose::Slides::Export](../)
* Könyvtár [Aspose.Slides](../../)