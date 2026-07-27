---
title: Register()
second_title: Referência da API Aspose.Slides para C++
description: Registra uma callback que será invocada quando o cancelamento for solicitado.
type: docs
weight: 40
url: /pt/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const method


Registra uma callback que será invocada quando o cancelamento for solicitado.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | A Action<> a ser executada quando o cancelamento for solicitado. |

### Valor de retorno

Um objeto [CancellationTokenRegistration](../../cancellationtokenregistration/) que pode ser usado para cancelar o registro da callback.
## Observações



Se o cancelamento já foi solicitado, a callback será invocada imediatamente. 

A callback deve ser de curta duração e não bloqueante, pois será executada na thread que chama Cancel() no [CancellationTokenSource](../../cancellationtokensource/). 

## Veja também

* Typedef [Action](../../../system/action/)
* Classe [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Classe [CancellationToken](../)
* Namespace [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)