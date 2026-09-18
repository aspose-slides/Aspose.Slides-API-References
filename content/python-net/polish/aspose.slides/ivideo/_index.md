---
title: IVideo class
second_title: Aspose.Slides dla Pythona przez .NET - Referencja API
description: 
type: docs
url: /pl/aspose.slides/ivideo/
---
## IVideo klasa

Reprezentuje wideo osadzone w prezentacji.

Typ IVideo udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`content_type`](/slides/python-net/pl/aspose.slides/ivideo/content_type/) | Zwraca typ MIME wideo, zakodowany w [`IVideo.binary_data`](/slides/python-net/pl/aspose.slides/ivideo/binary_data).<br/>            Tylko do odczytu **str**. |
| [`binary_data`](/slides/python-net/pl/aspose.slides/ivideo/binary_data/) | Zwraca kopię danych dźwięku. W przypadku dużej ilości danych rozważ użycie <br/>            [`IVideo.get_stream`](/slides/python-net/pl/aspose.slides/ivideo/get_stream) metoda aby zapobiec niepotrzebnemu ładowaniu danych wideo do pamięci <br/>            lub nawet OutOfMemoryException.<br/>            Tylko do odczytu **int**[]. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/pl/aspose.slides/ivideo/get_stream/#) | Zwraca strumień Stream do odczytu.<br/>            Użyj 'using' lub zamknij strumień po użyciu. |


### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)