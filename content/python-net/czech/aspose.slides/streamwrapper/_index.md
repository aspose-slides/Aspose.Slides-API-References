---
title: StreamWrapper class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/streamwrapper/
---
## StreamWrapper třída

Aspose.IO.Stream wrapper for COM interface.

The StreamWrapper type exposes the following members:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`stream`](/slides/python-net/cs/aspose.slides/streamwrapper/stream/) | Získá proud.<br/>            Pouze pro čtení **io.RawIOBase**. |
| [`can_read`](/slides/python-net/cs/aspose.slides/streamwrapper/can_read/) | Získá hodnotu indikující, zda aktuální proud podporuje čtení.<br/>            Pouze pro čtení **bool**. |
| [`can_seek`](/slides/python-net/cs/aspose.slides/streamwrapper/can_seek/) | Získá hodnotu indikující, zda aktuální proud podporuje posouvání.<br/>            Pouze pro čtení **bool**. |
| [`can_write`](/slides/python-net/cs/aspose.slides/streamwrapper/can_write/) | Získá hodnotu indikující, zda aktuální proud podporuje zápis.<br/>            Pouze pro čtení **bool**. |
| [`length`](/slides/python-net/cs/aspose.slides/streamwrapper/length/) | Získá délku v bajtech proudu.<br/>            Pouze pro čtení **int**. |
| [`position`](/slides/python-net/cs/aspose.slides/streamwrapper/position/) | Získá nebo nastaví pozici v aktuálním proudu.<br/>            Pouze pro čtení **int**. |

## Metody

| Method | Description |
| :- | :- |
| [`close(self)`](/slides/python-net/cs/aspose.slides/streamwrapper/close/#) | Uzavře aktuální proud a uvolní veškeré prostředky. |
| [`flush(self)`](/slides/python-net/cs/aspose.slides/streamwrapper/flush/#) | Vyprázdní všechny buffery tohoto proudu a způsobí, že se buferovaná data zapíšou do podkladového zařízení. |
| [`read(self, buffer, offset, count)`](/slides/python-net/cs/aspose.slides/streamwrapper/read/#bytes-int-int) | Přečte sekvenci bajtů z aktuálního proudu a posune pozici v proudu o počet přečtených bajtů. |
| [`read_byte(self)`](/slides/python-net/cs/aspose.slides/streamwrapper/read_byte/#) | Přečte bajt z proudu a posune pozici v proudu o jeden bajt, nebo vrátí -1, pokud je na konci proudu. |
| [`seek(self, offset, origin)`](/slides/python-net/cs/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | Nastaví pozici v aktuálním proudu |
| [`write(self, buffer, offset, count)`](/slides/python-net/cs/aspose.slides/streamwrapper/write/#bytes-int-int) | Zapíše sekvenci bajtů do aktuálního proudu a posune aktuální pozici v tomto proudu o počet zapsaných bajtů. |
| [`write_byte(self, value)`](/slides/python-net/cs/aspose.slides/streamwrapper/write_byte/#int) | Zapíše bajt na aktuální pozici v proudu a posune pozici v proudu o jeden bajt. |


### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)