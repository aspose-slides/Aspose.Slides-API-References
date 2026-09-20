---
title: IStreamWrapper class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/istreamwrapper/
---
## IStreamWrapper klass

Aspose.IO.Stream-omslag för COM-gränssnitt.

IStreamWrapper-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`stream`](/slides/python-net/sv/aspose.slides/istreamwrapper/stream/) | Hämtar en ström.<br/>            Skrivskyddad **io.RawIOBase**. |
| [`can_read`](/slides/python-net/sv/aspose.slides/istreamwrapper/can_read/) | Hämtar ett värde som indikerar om den aktuella strömmen stödjer läsning.<br/>            Skrivskyddad **bool**. |
| [`can_seek`](/slides/python-net/sv/aspose.slides/istreamwrapper/can_seek/) | Hämtar ett värde som indikerar om den aktuella strömmen stödjer sökning.<br/>            Skrivskyddad **bool**. |
| [`can_write`](/slides/python-net/sv/aspose.slides/istreamwrapper/can_write/) | Hämtar ett värde som indikerar om den aktuella strömmen stödjer skrivning.<br/>            Skrivskyddad **bool**. |
| [`length`](/slides/python-net/sv/aspose.slides/istreamwrapper/length/) | Hämtar längden i byte för strömmen.<br/>            Skrivskyddad **int**. |
| [`position`](/slides/python-net/sv/aspose.slides/istreamwrapper/position/) | Hämtar positionen i den aktuella strömmen.<br/>            Skrivskyddad **int**. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`close(self)`](/slides/python-net/sv/aspose.slides/istreamwrapper/close/#) | Stänger den aktuella strömmen och frigör eventuella resurser. |
| [`flush(self)`](/slides/python-net/sv/aspose.slides/istreamwrapper/flush/#) | Rensar alla buffertar för denna ström och får all buffrad data att skrivas till den underliggande enheten. |
| [`read(self, buffer, offset, count)`](/slides/python-net/sv/aspose.slides/istreamwrapper/read/#bytes-int-int) | Läser en sekvens av byte från den aktuella strömmen och förflyttar positionen i strömmen med antalet lästa byte. |
| [`read_byte(self)`](/slides/python-net/sv/aspose.slides/istreamwrapper/read_byte/#) | Läser ett byte från strömmen och förflyttar positionen i strömmen med ett byte, eller returnerar -1 om slutet på strömmen nås. |
| [`seek(self, offset, origin)`](/slides/python-net/sv/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | Sätter positionen i den aktuella strömmen |
| [`write(self, buffer, offset, count)`](/slides/python-net/sv/aspose.slides/istreamwrapper/write/#bytes-int-int) | Skriver en sekvens av byte till den aktuella strömmen och förflyttar den aktuella positionen i denna ström med antalet skrivna byte. |
| [`write_byte(self, value)`](/slides/python-net/sv/aspose.slides/istreamwrapper/write_byte/#int) | Skriver ett byte till den aktuella positionen i strömmen och förflyttar positionen i strömmen med ett byte. |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)