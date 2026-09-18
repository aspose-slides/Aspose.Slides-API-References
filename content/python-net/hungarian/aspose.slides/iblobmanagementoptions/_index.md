---
title: IBlobManagementOptions class
second_title: Aspose.Slides for Python via .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions osztály

A Binary Large Object (BLOB) egy bináris adat, amely egyetlen egységként van tárolva – például a BLOB lehet audio, video vagy akár a bemutató maga. Számos technikát használnak a memória fogyasztás optimalizálására a BLOB-ok kezelése során – legyen az már a bemutatóban tárolt vagy később programozottan hozzáadott. A [`IBlobManagementOptions`](/slides/python-net/hu/aspose.slides/iblobmanagementoptions) használatával különböző viselkedési aspektusokat módosíthat a BLOB-ok kezelésében a [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation) példány életciklusa során.

Az IBlobManagementOptions típus a következő tagokat biztosítja:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/hu/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | Ez a tulajdonság meghatározza, hogy a Presentation osztály egy példánya lehet-e a forrás - fájl <br/>            vagy adatfolyam - tulajdonosa a példány életciklusa alatt. Ha a példány tulajdonos, akkor zárolja a forrást. Ez segít <br/>            a memória fogyasztás és a teljesítmény javításában a BLOB-ok kezelése során, de a forrás (adatfolyam vagy fájl) <br/>            nem módosítható a Presentation példány életciklusa alatt. Ez egy példa: |
| [`is_temporary_files_allowed`](/slides/python-net/hu/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | Ez a tulajdonság meghatározza, hogy a BLOB-ok kezelése közben létrehozhatók-e ideiglenes fájlok, ami jelentősen <br/>            csökkenti a memória fogyasztást, de fájlok létrehozásához jogosultságot igényel.<br/>            Minden fájl törlésre kerül, miután a bemutatóval végzett munka befejeződik. |
| [`temp_files_root_path`](/slides/python-net/hu/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | Az a gyökér útvonal, ahol az ideiglenes fájlok létre lesznek hozva. Alapértelmezés szerint a rendszer ideiglenes könyvtára lesz használva. <br/>            A hosztolási folyamatnak jogosultsággal kell rendelkeznie <br/>            fájlok és mappák létrehozásához ott. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/hu/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | Meghatározza a maximális teljes méretet (bájtban), amelyet az összes BLOB elfoglalhat a memóriában. Alapértelmezés szerint az összes BLOB<br/>            memóriába van betöltve; csak akkor, amikor ez a határ elérve van, alkalmaznak alternatív mechanizmusokat (például ideiglenes<br/>            fájlok). A BLOB-ok memóriában tartása maximalizálja a teljesítményt, de magas memóriahasználathoz vezethet. Használja<br/>            ezt a tulajdonságot, hogy a viselkedést a környezetéhez vagy követelményeihez igazítsa. |

### Lásd még
* osztály [`IBlobManagementOptions`](/slides/python-net/hu/aspose.slides/iblobmanagementoptions)
* osztály [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)