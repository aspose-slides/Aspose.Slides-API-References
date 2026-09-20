---
title: IAudio class
second_title: Aspose.Slides pro Python přes .NET API Reference
description:
type: docs
url: /cs/aspose.slides/iaudio/
---
## IAudio třída

Reprezentuje vložený audio soubor.

Typ IAudio obsahuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`content_type`](/slides/python-net/cs/aspose.slides/iaudio/content_type/) | Vrací MIME typ audio, kódovaný v [`IAudio.binary_data`](/slides/python-net/cs/aspose.slides/iaudio/binary_data).<br/>            Pouze pro čtení **str**. |
| [`binary_data`](/slides/python-net/cs/aspose.slides/iaudio/binary_data/) | Vrací kopii dat audio. V případě velkého množství dat zvažte<br/>            použití metody [`IAudio.get_stream`](/slides/python-net/cs/aspose.slides/iaudio/get_stream) k zabránění zbytečnému načítání dat audio<br/>            do paměti nebo dokonce výjimky OutOfMemoryException.<br/>            Pouze pro čtení **int**[]. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/cs/aspose.slides/iaudio/get_stream/#) | Vrací Stream pro čtení.<br/>            Použijte 'using' nebo zavřete stream po použití. |


### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)