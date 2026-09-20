---
title: StreamWrapper class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/streamwrapper/
---
## StreamWrapper klass

Aspose.IO.Stream wrapper för COM-gränssnitt.

StreamWrapper-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`stream`](/slides/python-net/sv/aspose.slides/streamwrapper/stream/) | Hämtar en ström.<br/>            Skrivskyddad **io.RawIOBase**. |
| [`can_read`](/slides/python-net/sv/aspose.slides/streamwrapper/can_read/) | Hämtar ett värde som anger om den aktuella strömmen stöder läsning.<br/>            Skrivskyddad **bool**. |
| [`can_seek`](/slides/python-net/sv/aspose.slides/streamwrapper/can_seek/) | Hämtar ett värde som anger om den aktuella strömmen stöder sökning.<br/>            Skrivskyddad **bool**. |
| [`can_write`](/slides/python-net/sv/aspose.slides/streamwrapper/can_write/) | Hämtar ett värde som anger om den aktuella strömmen stöder skrivning.<br/>            Skrivskyddad **bool**. |
| [`length`](/slides/python-net/sv/aspose.slides/streamwrapper/length/) | Hämtar längden i byte för strömmen.<br/>            Skrivskyddad **int**. |
| [`position`](/slides/python-net/sv/aspose.slides/streamwrapper/position/) | Hämtar eller anger positionen i den aktuella strömmen.<br/>            Skrivskyddad **int**. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`close(self)`](/slides/python-net/sv/aspose.slides/streamwrapper/close/#) | Stänger den aktuella strömmen och frigör eventuella resurser. |
| [`flush(self)`](/slides/python-net/sv/aspose.slides/streamwrapper/flush/#) | Rensar alla buffertar för denna ström och får all buffrad data att skrivas till den underliggande enheten. |
| [`read(self, buffer, offset, count)`](/slides/python-net/sv/aspose.slides/streamwrapper/read/#bytes-int-int) | Läser en sekvens av byte från den aktuella strömmen och avancerar positionen i strömmen med antalet lästa byte. |
| [`read_byte(self)`](/slides/python-net/sv/aspose.slides/streamwrapper/read_byte/#) | Läser en byte från strömmen och avancerar positionen i strömmen med en byte, eller returnerar -1 om slutet på strömmen nås. |
| [`seek(self, offset, origin)`](/slides/python-net/sv/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | Anger positionen i den aktuella strömmen |
| [`write(self, buffer, offset, count)`](/slides/python-net/sv/aspose.slides/streamwrapper/write/#bytes-int-int) | Skriver en sekvens av byte till den aktuella strömmen och avancerar den aktuella positionen i denna ström med antalet skrivna byte. |
| [`write_byte(self, value)`](/slides/python-net/sv/aspose.slides/streamwrapper/write_byte/#int) | Skriver en byte till den aktuella positionen i strömmen och avancerar positionen i strömmen med en byte. |


### Se också
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)