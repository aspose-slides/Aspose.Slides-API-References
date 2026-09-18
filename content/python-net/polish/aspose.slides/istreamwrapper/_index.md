---
title: IStreamWrapper class
second_title: Aspose.Slides dla Pythona poprzez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/istreamwrapper/
---
## IStreamWrapper klasa

Aspose.IO.Stream wrapper for COM interface.

The IStreamWrapper type exposes the following members:

## Właściwości

| Property | Description |
| :- | :- |
| [`stream`](/slides/python-net/pl/aspose.slides/istreamwrapper/stream/) | Pobiera strumień.<br/>            Read-only **io.RawIOBase**. |
| [`can_read`](/slides/python-net/pl/aspose.slides/istreamwrapper/can_read/) | Pobiera wartość określającą, czy bieżący strumień obsługuje odczyt.<br/>            Read-only **bool**. |
| [`can_seek`](/slides/python-net/pl/aspose.slides/istreamwrapper/can_seek/) | Pobiera wartość określającą, czy bieżący strumień obsługuje przemieszczenie.<br/>            Read-only **bool**. |
| [`can_write`](/slides/python-net/pl/aspose.slides/istreamwrapper/can_write/) | Pobiera wartość określającą, czy bieżący strumień obsługuje zapisywanie.<br/>            Read-only **bool**. |
| [`length`](/slides/python-net/pl/aspose.slides/istreamwrapper/length/) | Pobiera długość strumienia w bajtach.<br/>            Read-only **int**. |
| [`position`](/slides/python-net/pl/aspose.slides/istreamwrapper/position/) | Pobiera pozycję w bieżącym strumieniu.<br/>            Read-only **int**. |

## Metody

| Method | Description |
| :- | :- |
| [`close(self)`](/slides/python-net/pl/aspose.slides/istreamwrapper/close/#) | Zamyka bieżący strumień i zwalnia wszystkie zasoby. |
| [`flush(self)`](/slides/python-net/pl/aspose.slides/istreamwrapper/flush/#) | Czyści wszystkie bufory tego strumienia i powoduje zapisanie wszelkich buforowanych danych do urządzenia podstawowego. |
| [`read(self, buffer, offset, count)`](/slides/python-net/pl/aspose.slides/istreamwrapper/read/#bytes-int-int) | Odczytuje sekwencję bajtów z bieżącego strumienia i przesuwa pozycję w strumieniu o liczbę odczytanych bajtów. |
| [`read_byte(self)`](/slides/python-net/pl/aspose.slides/istreamwrapper/read_byte/#) | Odczytuje bajt ze strumienia i przesuwa pozycję w strumieniu o jeden bajt, lub zwraca -1, jeśli jest koniec strumienia. |
| [`seek(self, offset, origin)`](/slides/python-net/pl/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | Ustawia pozycję w bieżącym strumieniu |
| [`write(self, buffer, offset, count)`](/slides/python-net/pl/aspose.slides/istreamwrapper/write/#bytes-int-int) | zapisuje sekwencję bajtów do bieżącego strumienia i przesuwa bieżącą pozycję w tym strumieniu o liczbę zapisanych bajtów. |
| [`write_byte(self, value)`](/slides/python-net/pl/aspose.slides/istreamwrapper/write_byte/#int) | Zapisuje bajt w bieżącej pozycji w strumieniu i przesuwa pozycję w strumieniu o jeden bajt. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)