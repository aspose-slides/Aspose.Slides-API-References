---
title: Audio class
second_title: Aspose.Slides dla Pythona przez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/audio/
---
## Audio klasa

Reprezentuje osadzony plik audio.

Typ Audio udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`content_type`](/slides/python-net/pl/aspose.slides/audio/content_type/) | Zwraca typ MIME audio, zakodowany w [`Audio.binary_data`](/slides/python-net/pl/aspose.slides/audio/binary_data).<br/>            Tylko do odczytu **str**. |
| [`binary_data`](/slides/python-net/pl/aspose.slides/audio/binary_data/) | Zwraca kopię danych audio. W przypadku dużej ilości danych rozważ <br/>            użycie metody [`Audio.get_stream`](/slides/python-net/pl/aspose.slides/audio/get_stream), aby zapobiec niepotrzebnemu ładowaniu danych audio<br/>            do pamięci lub nawet wyjątku OutOfMemoryException.<br/>            Tylko do odczytu **int**[]. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/pl/aspose.slides/audio/get_stream/#) | Zwraca strumień Stream do odczytu.<br/>            Użyj 'using' lub zamknij strumień po użyciu. |


### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)