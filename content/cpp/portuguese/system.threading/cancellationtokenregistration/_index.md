---
title: CancellationTokenRegistration
second_title: Referência da API Aspose.Slides para C++
description: Representa um registro para um callback de token de cancelamento.
type: docs
weight: 27
url: /pt/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration classe


Representa um registro para um callback de token de cancelamento.

```cpp
class CancellationTokenRegistration
```

## Métodos

| Método | Descrição |
| --- | --- |
| void [Dispose](./dispose/)() | Descarta o registro e remove a callback do [CancellationTokenSource](../cancellationtokensource/) associado. Depois de chamar este método, a callback registrada não será mais invocada quando o [CancellationTokenSource](../cancellationtokensource/) associado for cancelado. |
## Observações


Esta classe permite a desregistro de uma callback de um token de cancelamento. Quando descartada, ela remove a callback do [CancellationTokenSource](../cancellationtokensource/) associado. Esta classe não deve ser criada diretamente - ela é retornada pelos métodos de registro [CancellationToken](../cancellationtoken/). 

## Veja também

* Espaço de nomes [System::Threading](../)
* Biblioteca [Aspose.Slides](../../)