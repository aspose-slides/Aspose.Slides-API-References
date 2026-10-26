---
title: InterruptionToken class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/interruptiontoken/
---
## InterruptionToken classe

Esta classe representa o token a ser usado para sinalizar tarefas de longa duração se a interrupção foi solicitada.

O tipo InterruptionToken expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`none`](/slides/python-net/pt/aspose.slides/interruptiontoken/none/) | Representa um token de interrupção vazio.<br/>            As operações de longa duração nunca serão interrompidas via [`InterruptionTokenSource.interrupt`](/slides/python-net/pt/aspose.slides/interruptiontokensource/interrupt)<br/>            ao usar este token. |
| [`is_interruption_requested`](/slides/python-net/pt/aspose.slides/interruptiontoken/is_interruption_requested/) | Retorna **bool**.true se a interrupção foi solicitada. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`throw_if_interruption_requested(self)`](/slides/python-net/pt/aspose.slides/interruptiontoken/throw_if_interruption_requested/#) | Lança uma OperationCanceledException se<br/>            a interrupção foi solicitada. |


### Ver também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)