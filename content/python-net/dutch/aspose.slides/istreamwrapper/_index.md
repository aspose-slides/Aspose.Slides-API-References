---
title: IStreamWrapper class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/istreamwrapper/
---
## IStreamWrapper klasse

Aspose.IO.Stream-wrapper voor COM-interface.

Het IStreamWrapper-type geeft de volgende leden weer:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`stream`](/slides/python-net/nl/aspose.slides/istreamwrapper/stream/) | Haalt een stream op.<br/>            Alleen-lezen **io.RawIOBase**. |
| [`can_read`](/slides/python-net/nl/aspose.slides/istreamwrapper/can_read/) | Haalt een waarde op die aangeeft of de huidige stream lezen ondersteunt.<br/>            Alleen-lezen **bool**. |
| [`can_seek`](/slides/python-net/nl/aspose.slides/istreamwrapper/can_seek/) | Haalt een waarde op die aangeeft of de huidige stream zoeken ondersteunt.<br/>            Alleen-lezen **bool**. |
| [`can_write`](/slides/python-net/nl/aspose.slides/istreamwrapper/can_write/) | Haalt een waarde op die aangeeft of de huidige stream schrijven ondersteunt.<br/>            Alleen-lezen **bool**. |
| [`length`](/slides/python-net/nl/aspose.slides/istreamwrapper/length/) | Haalt de lengte in bytes van de stream op.<br/>            Alleen-lezen **int**. |
| [`position`](/slides/python-net/nl/aspose.slides/istreamwrapper/position/) | Haalt de positie binnen de huidige stream op.<br/>            Alleen-lezen **int**. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`close(self)`](/slides/python-net/nl/aspose.slides/istreamwrapper/close/#) | Sluit de huidige stream en geeft alle bronnen vrij. |
| [`flush(self)`](/slides/python-net/nl/aspose.slides/istreamwrapper/flush/#) | Wis alle buffers voor deze stream en zorgt ervoor dat gebufferde gegevens naar het onderliggende apparaat worden geschreven. |
| [`read(self, buffer, offset, count)`](/slides/python-net/nl/aspose.slides/istreamwrapper/read/#bytes-int-int) | Leest een reeks bytes van de huidige stream en schuift de positie binnen de stream vooruit met het aantal gelezen bytes. |
| [`read_byte(self)`](/slides/python-net/nl/aspose.slides/istreamwrapper/read_byte/#) | Leest een byte van de stream en schuift de positie binnen de stream met één byte vooruit, of retourneert -1 als het einde van de stream is bereikt. |
| [`seek(self, offset, origin)`](/slides/python-net/nl/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | Stelt de positie binnen de huidige stream in |
| [`write(self, buffer, offset, count)`](/slides/python-net/nl/aspose.slides/istreamwrapper/write/#bytes-int-int) | schrijft een reeks bytes naar de huidige stream en schuift de huidige positie binnen deze stream vooruit met het aantal geschreven bytes. |
| [`write_byte(self, value)`](/slides/python-net/nl/aspose.slides/istreamwrapper/write_byte/#int) | Schrijft een byte naar de huidige positie in de stream en schuift de positie binnen de stream met één byte vooruit. |


### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)