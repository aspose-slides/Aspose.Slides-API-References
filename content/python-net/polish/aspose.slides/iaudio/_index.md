---
title: IAudio class
second_title: Aspose.Slides dla Pythona – Referencja API .NET
description: 
type: docs
url: /pl/aspose.slides/iaudio/
---
## IAudio klasa

Represents an embedded audio file.

The IAudio type exposes the following members:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`content_type`](/slides/python-net/pl/aspose.slides/iaudio/content_type/) | Zwraca typ MIME audio, zakodowany w [`IAudio.binary_data`](/slides/python-net/pl/aspose.slides/iaudio/binary_data).<br/>            Tylko do odczytu **str**. |
| [`binary_data`](/slides/python-net/pl/aspose.slides/iaudio/binary_data/) | Zwraca kopię danych audio. W przypadku dużej ilości danych rozważ <br/>            użycie metody [`IAudio.get_stream`](/slides/python-net/pl/aspose.slides/iaudio/get_stream) aby zapobiec niepotrzebnemu ładowaniu danych audio<br/>            do pamięci lub nawet OutOfMemoryException.<br/>            Tylko do odczytu **int**[]. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/pl/aspose.slides/iaudio/get_stream/#) | Zwraca Stream stream do odczytu.<br/>            Użyj 'using' lub zamknij stream po użyciu. |


### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)