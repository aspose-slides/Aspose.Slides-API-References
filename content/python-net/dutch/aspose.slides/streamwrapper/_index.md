---
title: StreamWrapper class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/streamwrapper/
---
## StreamWrapper klasse

Aspose.IO.Stream wrapper voor COM-interface.

Het type StreamWrapper bevat de volgende leden:

## Eigenschappen

| Property | Description |
| :- | :- |
| [`stream`](/slides/python-net/nl/aspose.slides/streamwrapper/stream/) | Geeft een stream terug.<br/>            Alleen-lezen **io.RawIOBase**. |
| [`can_read`](/slides/python-net/nl/aspose.slides/streamwrapper/can_read/) | Geeft een waarde terug die aangeeft of de huidige stream lezen ondersteunt.<br/>            Alleen-lezen **bool**. |
| [`can_seek`](/slides/python-net/nl/aspose.slides/streamwrapper/can_seek/) | Geeft een waarde terug die aangeeft of de huidige stream zoeken ondersteunt.<br/>            Alleen-lezen **bool**. |
| [`can_write`](/slides/python-net/nl/aspose.slides/streamwrapper/can_write/) | Geeft een waarde terug die aangeeft of de huidige stream schrijven ondersteunt.<br/>            Alleen-lezen **bool**. |
| [`length`](/slides/python-net/nl/aspose.slides/streamwrapper/length/) | Geeft de lengte in bytes van de stream terug.<br/>            Alleen-lezen **int**. |
| [`position`](/slides/python-net/nl/aspose.slides/streamwrapper/position/) | Geeft de positie binnen de huidige stream terug of stelt deze in.<br/>            Alleen-lezen **int**. |

## Methoden

| Method | Description |
| :- | :- |
| [`close(self)`](/slides/python-net/nl/aspose.slides/streamwrapper/close/#) | Sluit de huidige stream en geeft alle bronnen vrij. |
| [`flush(self)`](/slides/python-net/nl/aspose.slides/streamwrapper/flush/#) | Wis alle buffers voor deze stream en zorgt ervoor dat alle gebufferde gegevens naar het onderliggende apparaat worden geschreven. |
| [`read(self, buffer, offset, count)`](/slides/python-net/nl/aspose.slides/streamwrapper/read/#bytes-int-int) | Leest een reeks bytes van de huidige stream en schuift de positie in de stream vooruit met het aantal gelezen bytes. |
| [`read_byte(self)`](/slides/python-net/nl/aspose.slides/streamwrapper/read_byte/#) | Leest één byte van de stream en schuift de positie in de stream één byte vooruit, of retourneert -1 als het einde van de stream is bereikt. |
| [`seek(self, offset, origin)`](/slides/python-net/nl/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | Stelt de positie binnen de huidige stream in |
| [`write(self, buffer, offset, count)`](/slides/python-net/nl/aspose.slides/streamwrapper/write/#bytes-int-int) | Schrijft een reeks bytes naar de huidige stream en schuift de huidige positie in deze stream vooruit met het aantal geschreven bytes. |
| [`write_byte(self, value)`](/slides/python-net/nl/aspose.slides/streamwrapper/write_byte/#int) | Schrijft één byte naar de huidige positie in de stream en schuift de positie in de stream één byte vooruit. |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)