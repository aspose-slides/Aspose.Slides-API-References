---
title: IStreamWrapper class
second_title: Aspose.Slides pro Python přes .NET API referenci
description: 
type: docs
url: /cs/aspose.slides/istreamwrapper/
---
## IStreamWrapper třída

Obal Aspose.IO.Stream pro rozhraní COM.

Typ IStreamWrapper exponuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`stream`](/slides/python-net/cs/aspose.slides/istreamwrapper/stream/) | Získá proud.<br/>            Pouze pro čtení **io.RawIOBase**. |
| [`can_read`](/slides/python-net/cs/aspose.slides/istreamwrapper/can_read/) | Získá hodnotu určující, zda aktuální proud podporuje čtení.<br/>            Pouze pro čtení **bool**. |
| [`can_seek`](/slides/python-net/cs/aspose.slides/istreamwrapper/can_seek/) | Získá hodnotu určující, zda aktuální proud podporuje hledání.<br/>            Pouze pro čtení **bool**. |
| [`can_write`](/slides/python-net/cs/aspose.slides/istreamwrapper/can_write/) | Získá hodnotu určující, zda aktuální proud podporuje zápis.<br/>            Pouze pro čtení **bool**. |
| [`length`](/slides/python-net/cs/aspose.slides/istreamwrapper/length/) | Získá délku proudu v bajtech.<br/>            Pouze pro čtení **int**. |
| [`position`](/slides/python-net/cs/aspose.slides/istreamwrapper/position/) | Získá pozici v aktuálním proudu.<br/>            Pouze pro čtení **int**. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`close(self)`](/slides/python-net/cs/aspose.slides/istreamwrapper/close/#) | Uzavře aktuální proud a uvolní všechny prostředky. |
| [`flush(self)`](/slides/python-net/cs/aspose.slides/istreamwrapper/flush/#) | Vyprázdní všechny buffery tohoto proudu a způsobí, že se bufferovaná data zapíší do podkladového zařízení. |
| [`read(self, buffer, offset, count)`](/slides/python-net/cs/aspose.slides/istreamwrapper/read/#bytes-int-int) | Čte sekvenci bajtů z aktuálního proudu a posune pozici v proudu o počet přečtených bajtů. |
| [`read_byte(self)`](/slides/python-net/cs/aspose.slides/istreamwrapper/read_byte/#) | Čte bajt z proudu a posune pozici v proudu o jeden bajt, nebo vrátí -1 pokud je na konci proudu. |
| [`seek(self, offset, origin)`](/slides/python-net/cs/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | Nastaví pozici v aktuálním proudu |
| [`write(self, buffer, offset, count)`](/slides/python-net/cs/aspose.slides/istreamwrapper/write/#bytes-int-int) | Zapisuje sekvenci bajtů do aktuálního proudu a posune aktuální pozici v tomto proudu o počet zapsaných bajtů. |
| [`write_byte(self, value)`](/slides/python-net/cs/aspose.slides/istreamwrapper/write_byte/#int) | Zapisuje bajt na aktuální pozici v proudu a posune pozici v proudu o jeden bajt. |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)