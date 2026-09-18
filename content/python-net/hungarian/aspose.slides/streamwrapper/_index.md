---
title: StreamWrapper class
second_title: Aspose.Slides a Python számára a .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/streamwrapper/
---
## StreamWrapper osztály

Aspose.IO.Stream wrapper for COM interface.

The StreamWrapper type exposes the following members:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`stream`](/slides/python-net/hu/aspose.slides/streamwrapper/stream/) | Lekéri egy stream-et.<br/>            Csak olvasható **io.RawIOBase**. |
| [`can_read`](/slides/python-net/hu/aspose.slides/streamwrapper/can_read/) | Lekéri azt az értéket, amely jelzi, hogy a jelenlegi stream támogatja-e az olvasást.<br/>            Csak olvasható **bool**. |
| [`can_seek`](/slides/python-net/hu/aspose.slides/streamwrapper/can_seek/) | Lekéri azt az értéket, amely jelzi, hogy a jelenlegi stream támogatja-e a pozicionálást.<br/>            Csak olvasható **bool**. |
| [`can_write`](/slides/python-net/hu/aspose.slides/streamwrapper/can_write/) | Lekéri azt az értéket, amely jelzi, hogy a jelenlegi stream támogatja-e az írást.<br/>            Csak olvasható **bool**. |
| [`length`](/slides/python-net/hu/aspose.slides/streamwrapper/length/) | Lekéri a stream hosszát bájtokban.<br/>            Csak olvasható **int**. |
| [`position`](/slides/python-net/hu/aspose.slides/streamwrapper/position/) | Lekéri vagy beállítja a pozíciót a jelenlegi stream-ben.<br/>            Csak olvasható **int**. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`close(self)`](/slides/python-net/hu/aspose.slides/streamwrapper/close/#) | Bezárja a jelenlegi stream-et és felszabadítja az összes erőforrást. |
| [`flush(self)`](/slides/python-net/hu/aspose.slides/streamwrapper/flush/#) | Kiüríti az összes puffert ennél a stream-nél, és a pufferelt adatokat az alatta lévő eszközre írja. |
| [`read(self, buffer, offset, count)`](/slides/python-net/hu/aspose.slides/streamwrapper/read/#bytes-int-int) | Olvas egy bájtsorozatot a jelenlegi stream-ből, és a stream pozícióját a beolvasott bájtok számával növeli. |
| [`read_byte(self)`](/slides/python-net/hu/aspose.slides/streamwrapper/read_byte/#) | Olvas egy bájtot a stream-ből, és a stream pozícióját egy bájttal növeli, vagy -1-et ad vissza, ha a stream végén vagyunk. |
| [`seek(self, offset, origin)`](/slides/python-net/hu/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | Beállítja a pozíciót a jelenlegi stream-ben |
| [`write(self, buffer, offset, count)`](/slides/python-net/hu/aspose.slides/streamwrapper/write/#bytes-int-int) | Ír egy bájtsorozatot a jelenlegi stream-be, és a stream aktuális pozícióját a leírt bájtok számával növeli. |
| [`write_byte(self, value)`](/slides/python-net/hu/aspose.slides/streamwrapper/write_byte/#int) | Ír egy bájtot a stream aktuális pozíciójába, és a stream pozícióját egy bájttal növeli. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)