---
title: IStreamWrapper class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/istreamwrapper/
---
## IStreamWrapper Klasse

Aspose.IO.Stream wrapper for COM interface.

The IStreamWrapper type exposes the following members:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`stream`](/slides/python-net/de/aspose.slides/istreamwrapper/stream/) | Liefert einen Stream.<br/>            Nur-Lesen **io.RawIOBase**. |
| [`can_read`](/slides/python-net/de/aspose.slides/istreamwrapper/can_read/) | Liefert einen Wert, der angibt, ob der aktuelle Stream das Lesen unterstützt.<br/>            Nur-Lesen **bool**. |
| [`can_seek`](/slides/python-net/de/aspose.slides/istreamwrapper/can_seek/) | Liefert einen Wert, der angibt, ob der aktuelle Stream das Suchen unterstützt.<br/>            Nur-Lesen **bool**. |
| [`can_write`](/slides/python-net/de/aspose.slides/istreamwrapper/can_write/) | Liefert einen Wert, der angibt, ob der aktuelle Stream das Schreiben unterstützt.<br/>            Nur-Lesen **bool**. |
| [`length`](/slides/python-net/de/aspose.slides/istreamwrapper/length/) | Liefert die Länge des Streams in Bytes.<br/>            Nur-Lesen **int**. |
| [`position`](/slides/python-net/de/aspose.slides/istreamwrapper/position/) | Liefert die Position im aktuellen Stream.<br/>            Nur-Lesen **int**. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`close(self)`](/slides/python-net/de/aspose.slides/istreamwrapper/close/#) | Schließt den aktuellen Stream und gibt alle Ressourcen frei. |
| [`flush(self)`](/slides/python-net/de/aspose.slides/istreamwrapper/flush/#) | Löscht alle Puffer für diesen Stream und bewirkt, dass gepufferte Daten in das zugrunde liegende Gerät geschrieben werden. |
| [`read(self, buffer, offset, count)`](/slides/python-net/de/aspose.slides/istreamwrapper/read/#bytes-int-int) | Liest eine Sequenz von Bytes aus dem aktuellen Stream und erhöht die Position im Stream um die gelesene Anzahl von Bytes. |
| [`read_byte(self)`](/slides/python-net/de/aspose.slides/istreamwrapper/read_byte/#) | Liest ein Byte aus dem Stream und erhöht die Position im Stream um ein Byte, oder gibt -1 zurück, wenn das Ende des Streams erreicht ist. |
| [`seek(self, offset, origin)`](/slides/python-net/de/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | Setzt die Position im aktuellen Stream |
| [`write(self, buffer, offset, count)`](/slides/python-net/de/aspose.slides/istreamwrapper/write/#bytes-int-int) | Schreibt eine Sequenz von Bytes in den aktuellen Stream und erhöht die aktuelle Position in diesem Stream um die geschriebene Anzahl von Bytes. |
| [`write_byte(self, value)`](/slides/python-net/de/aspose.slides/istreamwrapper/write_byte/#int) | Schreibt ein Byte an die aktuelle Position im Stream und erhöht die Position im Stream um ein Byte. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)