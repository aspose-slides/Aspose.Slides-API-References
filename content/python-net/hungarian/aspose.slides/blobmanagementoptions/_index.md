---
title: BlobManagementOptions class
second_title: Aspose.Slides a Python számára .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions osztály

A BLOB-kezelési szabályok és egyéb BLOB beállítások kezelésére használható beállításokat képviseli.

A BlobManagementOptions típus a következő tagokat teszi elérhetővé:

## Konstruktorok

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides/blobmanagementoptions/__init__/#) | Új alapértelmezett blob kezelési beállításokat hoz létre. |

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/hu/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | Ez a tulajdonság meghatározza, hogy a Presentation osztály példánya lehet-e a forrás – fájl <br/>            vagy adatfolyam tulajdonosa az példány életciklusa alatt. Ha a példány tulajdonos, akkor zárolja a forrást. Ez segít <br/>            a memóriafogyasztás és a teljesítmény javításában BLOB-ok használata közben, de a forrás (adatfolyam vagy fájl) <br/>            nem változtatható meg a Presentation példány életciklusa során. |
| [`is_temporary_files_allowed`](/slides/python-net/hu/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | Ez a tulajdonság meghatározza, hogy ideiglenes fájlok hozhatók-e létre BLOB-ok használata közben, ami jelentősen <br/>            csökkenti a memóriafogyasztást, de fájlok létrehozásához engedélyt igényel.<br/>            Minden fájl törlésre kerül, miután a prezentációval végzett munka befejeződött. |
| [`temp_files_root_path`](/slides/python-net/hu/aspose.slides/blobmanagementoptions/temp_files_root_path/) | A gyökérútvonal, ahol az ideiglenes fájlok létre lesznek hozva. Alapértelmezés szerint a rendszer ideiglenes könyvtára lesz használva. <br/>            A fogadó folyamatnak rendelkeznie kell a megfelelő engedélyekkel <br/>            fájlok és mappák létrehozásához. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/hu/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | Meghatározza a maximális összméretet (bájtban), amelyet az összes BLOB elfoglalhat a memóriában. Alapértelmezés szerint az összes BLOB<br/>            a memóriába töltődik; csak amikor ez a korlát elérhető, kerülnek alkalmazásra alternatív mechanizmusok (például ideiglenes<br/>            fájlok). A BLOB-ok memóriában tartása maximalizálja a teljesítményt, de magas memóriahasználathoz vezethet. Használja<br/>            ezt a tulajdonságot a viselkedés környezethez vagy követelményekhez történő igazításához. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)