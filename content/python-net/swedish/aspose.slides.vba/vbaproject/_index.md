---
title: VbaProject class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.vba/vbaproject/
---
## VbaProject klass

Representerar VBA-projekt med presentationsmakron.

VbaProject-typen exponerar följande medlemmar:

## Konstruktörer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides.vba/vbaproject/__init__/#) | Den här konstruktorn skapar ett nytt VBA-projekt från början.<br/>            Projektet kommer att skapas i 1252 Windows Latin 1 (ANSI) kodsida |
| [`__init__(self, data)`](/slides/python-net/sv/aspose.slides.vba/vbaproject/__init__/#bytes) | Den här konstruktorn laddar VBA-projekt från binär representation av OLE-behållare. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`name`](/slides/python-net/sv/aspose.slides.vba/vbaproject/name/) | Returnerar namnet på VBA-projektet.<br/>            Read-only **str**. |
| [`modules`](/slides/python-net/sv/aspose.slides.vba/vbaproject/modules/) | Returnerar listan över alla moduler som ingår i VBA-projektet.<br/>            Read-only [`IVbaModuleCollection`](/slides/python-net/sv/aspose.slides.vba/ivbamodulecollection). |
| [`references`](/slides/python-net/sv/aspose.slides.vba/vbaproject/references/) | Returnerar listan över alla referenser som ingår i VBA-projektet.<br/>            Read-only [`IVbaReferenceCollection`](/slides/python-net/sv/aspose.slides.vba/ivbareferencecollection). |
| [`is_password_protected`](/slides/python-net/sv/aspose.slides.vba/vbaproject/is_password_protected/) | Indikerar om VBAProject är skyddad med ett lösenord för att visa projektegenskaper.<br/>            Read-only **bool**. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`to_binary(self)`](/slides/python-net/sv/aspose.slides.vba/vbaproject/to_binary/#) | Returnerar den binära representationen av VBA-projektet som OLE-behållare |

### Se även
* modul [`aspose.slides.vba`](/slides/python-net/sv/aspose.slides.vba)
* bibliotek [`Aspose.Slides`](/slides/python-net)