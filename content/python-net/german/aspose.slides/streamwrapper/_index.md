---
title: StreamWrapper class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/streamwrapper/
---
## StreamWrapper Klasse

Aspose.IO.Stream Wrapper für COM-Schnittstelle.

Der Typ StreamWrapper stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`stream`](/slides/python-net/de/aspose.slides/streamwrapper/stream/) | Liefert einen Stream.<br/>            Schreibgeschützt **io.RawIOBase**. |
| [`can_read`](/slides/python-net/de/aspose.slides/streamwrapper/can_read/) | Liefert einen Wert, der angibt, ob der aktuelle Stream das Lesen unterstützt.<br/>            Schreibgeschützt **bool**. |
| [`can_seek`](/slides/python-net/de/aspose.slides/streamwrapper/can_seek/) | Liefert einen Wert, der angibt, ob der aktuelle Stream das Suchen unterstützt.<br/>            Schreibgeschützt **bool**. |
| [`can_write`](/slides/python-net/de/aspose.slides/streamwrapper/can_write/) | Liefert einen Wert, der angibt, ob der aktuelle Stream das Schreiben unterstützt.<br/>            Schreibgeschützt **bool**. |
| [`length`](/slides/python-net/de/aspose.slides/streamwrapper/length/) | Liefert die Länge des Streams in Bytes.<br/>            Schreibgeschützt **int**. |
| [`position`](/slides/python-net/de/aspose.slides/streamwrapper/position/) | Liefert oder setzt die Position im aktuellen Stream.<br/>            Schreibgeschützt **int**. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`close(self)`](/slides/python-net/de/aspose.slides/streamwrapper/close/#) | Schließt den aktuellen Stream und gibt alle Ressourcen frei. |
| [`flush(self)`](/slides/python-net/de/aspose.slides/streamwrapper/flush/#) | Leert alle Puffer dieses Streams und bewirkt, dass gepufferte Daten an das zugrunde liegende Gerät geschrieben werden. |
| [`read(self, buffer, offset, count)`](/slides/python-net/de/aspose.slides/streamwrapper/read/#bytes-int-int) | Liest eine Sequenz von Bytes aus dem aktuellen Stream und verschiebt die Position im Stream um die gelesene Anzahl von Bytes. |
| [`read_byte(self)`](/slides/python-net/de/aspose.slides/streamwrapper/read_byte/#) | Liest ein Byte aus dem Stream und verschiebt die Position im Stream um ein Byte, oder gibt -1 zurück, wenn das Ende des Streams erreicht ist. |
| [`seek(self, offset, origin)`](/slides/python-net/de/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | Setzt die Position im aktuellen Stream |
| [`write(self, buffer, offset, count)`](/slides/python-net/de/aspose.slides/streamwrapper/write/#bytes-int-int) | schreibt eine Sequenz von Bytes in den aktuellen Stream und verschiebt die aktuelle Position in diesem Stream um die geschriebene Anzahl von Bytes. |
| [`write_byte(self, value)`](/slides/python-net/de/aspose.slides/streamwrapper/write_byte/#int) | Schreibt ein Byte an die aktuelle Position im Stream und verschiebt die Position im Stream um ein Byte. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)