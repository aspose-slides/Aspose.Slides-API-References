---
title: Audio class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/audio/
---
## Audio třída

Representuje vložený audio soubor.

Typ Audio poskytuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`content_type`](/slides/python-net/cs/aspose.slides/audio/content_type/) | Vrací MIME typ audio, kódovaný v [`Audio.binary_data`](/slides/python-net/cs/aspose.slides/audio/binary_data).<br/>            Pouze pro čtení **str**. |
| [`binary_data`](/slides/python-net/cs/aspose.slides/audio/binary_data/) | Vrací kopii dat audio. V případě velkého množství dat zvažte <br/>            použití metody [`Audio.get_stream`](/slides/python-net/cs/aspose.slides/audio/get_stream) k zabránění zbytečnému načítání dat audio<br/>            do paměti nebo dokonce OutOfMemoryException.<br/>            Pouze pro čtení **int**[]. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/cs/aspose.slides/audio/get_stream/#) | Vrací Stream stream pro čtení.<br/>            Použijte 'using' nebo po použití zavřete stream. |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)