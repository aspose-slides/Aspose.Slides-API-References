---
title: StreamWrapper class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/streamwrapper/
---
## classe StreamWrapper

Invólucro Aspose.IO.Stream para interface COM.

O tipo StreamWrapper expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`stream`](/slides/python-net/pt/aspose.slides/streamwrapper/stream/) | Obtém um fluxo.<br/>            Somente leitura **io.RawIOBase**. |
| [`can_read`](/slides/python-net/pt/aspose.slides/streamwrapper/can_read/) | Obtém um valor que indica se o fluxo atual suporta leitura.<br/>            Somente leitura **bool**. |
| [`can_seek`](/slides/python-net/pt/aspose.slides/streamwrapper/can_seek/) | Obtém um valor que indica se o fluxo atual suporta busca.<br/>            Somente leitura **bool**. |
| [`can_write`](/slides/python-net/pt/aspose.slides/streamwrapper/can_write/) | Obtém um valor que indica se o fluxo atual suporta gravação.<br/>            Somente leitura **bool**. |
| [`length`](/slides/python-net/pt/aspose.slides/streamwrapper/length/) | Obtém o comprimento em bytes do fluxo.<br/>            Somente leitura **int**. |
| [`position`](/slides/python-net/pt/aspose.slides/streamwrapper/position/) | Obtém ou define a posição dentro do fluxo atual.<br/>            Somente leitura **int**. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`close(self)`](/slides/python-net/pt/aspose.slides/streamwrapper/close/#) | Fecha o fluxo atual e libera quaisquer recursos. |
| [`flush(self)`](/slides/python-net/pt/aspose.slides/streamwrapper/flush/#) | Limpa todos os buffers deste fluxo e faz com que quaisquer dados armazenados sejam gravados no dispositivo subjacente. |
| [`read(self, buffer, offset, count)`](/slides/python-net/pt/aspose.slides/streamwrapper/read/#bytes-int-int) | Lê uma sequência de bytes do fluxo atual e avança a posição dentro do fluxo pelo número de bytes lidos. |
| [`read_byte(self)`](/slides/python-net/pt/aspose.slides/streamwrapper/read_byte/#) | Lê um byte do fluxo e avança a posição dentro do fluxo em um byte, ou retorna -1 se estiver no final do fluxo. |
| [`seek(self, offset, origin)`](/slides/python-net/pt/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | Define a posição dentro do fluxo atual |
| [`write(self, buffer, offset, count)`](/slides/python-net/pt/aspose.slides/streamwrapper/write/#bytes-int-int) | grava uma sequência de bytes no fluxo atual e avança a posição atual dentro deste fluxo pelo número de bytes gravados. |
| [`write_byte(self, value)`](/slides/python-net/pt/aspose.slides/streamwrapper/write_byte/#int) | Grava um byte na posição atual do fluxo e avança a posição dentro do fluxo em um byte. |


### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)