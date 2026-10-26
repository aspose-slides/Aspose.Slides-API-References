---
title: EmbeddingLevel enumeration
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/embeddinglevel/
---
## EmbeddingLevel enumeráció

A betűkészlet beágyazására vonatkozó licencjogokat képviseli.

Az EmbeddingLevel típus a következő tagokat teszi közzé:

## Mezők

| Mező | Leírás |
| :- | :- |
| INSTALLABLE | Az ezzel a beállítással rendelkező betűkészletek jelzik, hogy beágyazhatók és állandóan telepíthetők a távoli rendszerre egy alkalmazás által. <br/>            A távoli rendszer felhasználója ugyanazokat a jogokat, kötelezettségeket és licenceket kapja meg a betűkészletre, mint a betűkészlet eredeti vásárlója, <br/>            és ugyanazon végfelhasználói licencszerződés, szerzői jog, formatervezési szabadalom és/vagy védjegy hatálya alá tartozik, mint az eredeti vásárló. |
| RESTRICTED | Azok a betűkészletek, amelyeknél csak ez a bit van beállítva, nem módosíthatók, beágyazhatók vagy cserélhetők semmilyen módon, mielőtt előzetesen megszerezték a jogtulajdonos engedélyét. |
| PREVIEW_PRINT | Ha ez a bit be van állítva, a betűkészlet beágyazható, és ideiglenesen betöltődik a távoli rendszerre. A Preview & <br/>            Print betűkészleteket tartalmazó dokumentumokat csak "read-only" módban lehet megnyitni; a dokumentumot nem lehet szerkeszteni. |
| EDITABLE | Ha ez a bit be van állítva, a betűkészlet beágyazható, de csak ideiglenesen telepíthető más rendszerekre. A Preview & <br/>            Print betűkészletekkel ellentétben az Editable betűkészleteket tartalmazó dokumentumok olvasásra megnyithatók, a szerkesztés engedélyezett, és a változtatásokat menteni lehet. |
| NO_SUBSETTING | Ha ez a bit be van állítva, a betűkészletet nem szabad részhalmazra szűrni a beágyazás előtt. A 0-3 és 9 bitekben megadott további beágyazási korlátozások is érvényesek. |
| BITMAP_ONLY | Ha ez a bit be van állítva, csak a betűkészletben található bitmap képek ágyazhatók be. Kontúradatok nem ágyazhatók be. Ha a betűkészletben nincsenek bitmap képek, <br/>            akkor a betűkészletet nem lehet beágyazni, és a beágyazási szolgáltatások hibát fognak jelezni. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)