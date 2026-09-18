---
title: IStreamWrapper class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/istreamwrapper/
---
## IStreamWrapper classe

Wrapper Aspose.IO.Stream para interface COM.

O tipo IStreamWrapper expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`stream`](/slides/python-net/pt/aspose.slides/istreamwrapper/stream/) | Obtém um fluxo.<br/>            Somente leitura **io.RawIOBase**. |
| [`can_read`](/slides/python-net/pt/aspose.slides/istreamwrapper/can_read/) | Obtém um valor que indica se o fluxo atual suporta leitura.<br/>            Somente leitura **bool**. |
| [`can_seek`](/slides/python-net/pt/aspose.slides/istreamwrapper/can_seek/) | Obtém um valor que indica se o fluxo atual suporta busca.<br/>            Somente leitura **bool**. |
| [`can_write`](/slides/python-net/pt/aspose.slides/istreamwrapper/can_write/) | Obtém um valor que indica se o fluxo atual suporta gravação.<br/>            Somente leitura **bool**. |
| [`length`](/slides/python-net/pt/aspose.slides/istreamwrapper/length/) | Obtém o comprimento em bytes do fluxo.<br/>            Somente leitura **int**. |
| [`position`](/slides/python-net/pt/aspose.slides/istreamwrapper/position/) | Obtém a posição dentro do fluxo atual.<br/>            Somente leitura **int**. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`close(self)`](/slides/python-net/pt/aspose.slides/istreamwrapper/close/#) | Fecha o fluxo atual e libera quaisquer recursos. |
| [`flush(self)`](/slides/python-net/pt/aspose.slides/istreamwrapper/flush/#) | Limpa todos os buffers deste fluxo e faz com que quaisquer dados em buffer sejam gravados no dispositivo subjacente. |
| [`read(self, buffer, offset, count)`](/slides/python-net/pt/aspose.slides/istreamwrapper/read/#bytes-int-int) | Lê uma sequência de bytes do fluxo atual e avança a posição no fluxo pelo número de bytes lidos. |
| [`read_byte(self)`](/slides/python-net/pt/aspose.slides/istreamwrapper/read_byte/#) | Lê um byte do fluxo e avança a posição no fluxo em um byte, ou retorna -1 se estiver no final do fluxo. |
| [`seek(self, offset, origin)`](/slides/python-net/pt/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | Define a posição dentro do fluxo atual |
| [`write(self, buffer, offset, count)`](/slides/python-net/pt/aspose.slides/istreamwrapper/write/#bytes-int-int) | Grava uma sequência de bytes no fluxo atual e avança a posição atual neste fluxo pelo número de bytes gravados. |
| [`write_byte(self, value)`](/slides/python-net/pt/aspose.slides/istreamwrapper/write_byte/#int) | Grava um byte na posição atual no fluxo e avança a posição no fluxo em um byte. |


### Veja também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)