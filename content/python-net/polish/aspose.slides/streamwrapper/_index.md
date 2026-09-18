---
title: StreamWrapper class
second_title: Aspose.Slides dla Pythona – odniesienie API .NET
description: 
type: docs
url: /pl/aspose.slides/streamwrapper/
---
## StreamWrapper klasa

Opakowanie Aspose.IO.Stream dla interfejsu COM.

Typ StreamWrapper udostępnia następujące elementy:

## Właściwości

| Property | Description |
| :- | :- |
| [`stream`](/slides/python-net/pl/aspose.slides/streamwrapper/stream/) | Zwraca strumień.<br/>            tylko do odczytu **io.RawIOBase**. |
| [`can_read`](/slides/python-net/pl/aspose.slides/streamwrapper/can_read/) | Zwraca wartość wskazującą, czy bieżący strumień obsługuje odczyt.<br/>            tylko do odczytu **bool**. |
| [`can_seek`](/slides/python-net/pl/aspose.slides/streamwrapper/can_seek/) | Zwraca wartość wskazującą, czy bieżący strumień obsługuje przeszukiwanie.<br/>            tylko do odczytu **bool**. |
| [`can_write`](/slides/python-net/pl/aspose.slides/streamwrapper/can_write/) | Zwraca wartość wskazującą, czy bieżący strumień obsługuje zapis.<br/>            tylko do odczytu **bool**. |
| [`length`](/slides/python-net/pl/aspose.slides/streamwrapper/length/) | Zwraca długość w bajtach strumienia.<br/>            tylko do odczytu **int**. |
| [`position`](/slides/python-net/pl/aspose.slides/streamwrapper/position/) | Zwraca lub ustawia pozycję w bieżącym strumieniu.<br/>            tylko do odczytu **int**. |

## Metody

| Method | Description |
| :- | :- |
| [`close(self)`](/slides/python-net/pl/aspose.slides/streamwrapper/close/#) | Zamyka bieżący strumień i zwalnia wszystkie zasoby. |
| [`flush(self)`](/slides/python-net/pl/aspose.slides/streamwrapper/flush/#) | Czyści wszystkie bufory tego strumienia i powoduje, że wszystkie zbuforowane dane są zapisywane do urządzenia podstawowego. |
| [`read(self, buffer, offset, count)`](/slides/python-net/pl/aspose.slides/streamwrapper/read/#bytes-int-int) | Odczytuje sekwencję bajtów z bieżącego strumienia i przesuwa pozycję w strumieniu o liczbę odczytanych bajtów. |
| [`read_byte(self)`](/slides/python-net/pl/aspose.slides/streamwrapper/read_byte/#) | Odczytuje bajt ze strumienia i przesuwa pozycję w strumieniu o jeden bajt, lub zwraca -1, jeśli znajduje się na końcu strumienia. |
| [`seek(self, offset, origin)`](/slides/python-net/pl/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | Ustawia pozycję w bieżącym strumieniu |
| [`write(self, buffer, offset, count)`](/slides/python-net/pl/aspose.slides/streamwrapper/write/#bytes-int-int) | Zapisuje sekwencję bajtów do bieżącego strumienia i przesuwa bieżącą pozycję w tym strumieniu o liczbę zapisanych bajtów. |
| [`write_byte(self, value)`](/slides/python-net/pl/aspose.slides/streamwrapper/write_byte/#int) | Zapisuje bajt w bieżącej pozycji w strumieniu i przesuwa pozycję w strumieniu o jeden bajt. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)