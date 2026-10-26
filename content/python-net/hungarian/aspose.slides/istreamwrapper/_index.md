---
title: IStreamWrapper class
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/istreamwrapper/
---
## IStreamWrapper osztály

Aspose.IO.Stream burkoló a COM interfészhez.

The IStreamWrapper type exposes the following members:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`stream`](/slides/python-net/hu/aspose.slides/istreamwrapper/stream/) | Lekéri az adatfolyamot.<br/>            Csak olvasható **io.RawIOBase**. |
| [`can_read`](/slides/python-net/hu/aspose.slides/istreamwrapper/can_read/) | Lekéri azt az értéket, amely megadja, hogy az aktuális adatfolyam támogatja-e a olvasást.<br/>            Csak olvasható **bool**. |
| [`can_seek`](/slides/python-net/hu/aspose.slides/istreamwrapper/can_seek/) | Lekéri azt az értéket, amely megadja, hogy az aktuális adatfolyam támogatja-e a keresést.<br/>            Csak olvasható **bool**. |
| [`can_write`](/slides/python-net/hu/aspose.slides/istreamwrapper/can_write/) | Lekéri azt az értéket, amely megadja, hogy az aktuális adatfolyam támogatja-e a írást.<br/>            Csak olvasható **bool**. |
| [`length`](/slides/python-net/hu/aspose.slides/istreamwrapper/length/) | Lekéri az adatfolyam hosszát bájtokban.<br/>            Csak olvasható **int**. |
| [`position`](/slides/python-net/hu/aspose.slides/istreamwrapper/position/) | Lekéri a pozíciót az aktuális adatfolyamban.<br/>            Csak olvasható **int**. |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`close(self)`](/slides/python-net/hu/aspose.slides/istreamwrapper/close/#) | Lezárja az aktuális adatfolyamot és felszabadít minden erőforrást. |
| [`flush(self)`](/slides/python-net/hu/aspose.slides/istreamwrapper/flush/#) | Törli az adatfolyam összes puffert, és az írásra váró adatot az alapvető eszközre küldi. |
| [`read(self, buffer, offset, count)`](/slides/python-net/hu/aspose.slides/istreamwrapper/read/#bytes-int-int) | Olvas egy bájtsorozatot az aktuális adatfolyamból, és a pozíciót a beolvasott bájtok számával növeli. |
| [`read_byte(self)`](/slides/python-net/hu/aspose.slides/istreamwrapper/read_byte/#) | Olvas egy bájtot az adatfolyamból, és a pozíciót egy bájttal növeli, vagy -1-et ad vissza, ha az adatfolyam végén van. |
| [`seek(self, offset, origin)`](/slides/python-net/hu/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | Beállítja a pozíciót az aktuális adatfolyamban |
| [`write(self, buffer, offset, count)`](/slides/python-net/hu/aspose.slides/istreamwrapper/write/#bytes-int-int) | ír egy bájtsorozatot az aktuális adatfolyamba és a pozíciót a írt bájtok számával növeli. |
| [`write_byte(self, value)`](/slides/python-net/hu/aspose.slides/istreamwrapper/write_byte/#int) | Ír egy bájtot az adatfolyam aktuális pozíciójába, és a pozíciót egy bájttal növeli. |


### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)