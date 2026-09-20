---
title: IVideo class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ivideo/
---
## IVideo třída

Reprezentuje video vložené do prezentace.

Typ IVideo vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`content_type`](/slides/python-net/cs/aspose.slides/ivideo/content_type/) | Vrací MIME typ videa, kódovaný v [`IVideo.binary_data`](/slides/python-net/cs/aspose.slides/ivideo/binary_data).<br/>            Pouze pro čtení **str**. |
| [`binary_data`](/slides/python-net/cs/aspose.slides/ivideo/binary_data/) | Vrací kopii dat zvuku. V případě velkého množství dat zvažte použití <br/>            [`IVideo.get_stream`](/slides/python-net/cs/aspose.slides/ivideo/get_stream) metody k zabránění zbytečnému načítání dat videa do paměti <br/>            nebo dokonce výjimky OutOfMemoryException.<br/>            Pouze pro čtení **int**[]. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/cs/aspose.slides/ivideo/get_stream/#) | Vrací Stream pro čtení.<br/>            Použijte 'using' nebo uzavřete stream po použití. |


### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)