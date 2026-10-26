---
title: CancellationToken
second_title: Referência da API Aspose.Slides para C++
description: Propaga notificação de que as operações devem ser canceladas. Esta classe fornece um mecanismo de cancelamento cooperativo entre threads, permitindo que uma thread notifique outras de que uma operação deve ser cancelada.
type: docs
weight: 14
url: /pt/system.threading/cancellationtoken/
---
## CancellationToken classe

Propaga notificação de que as operações devem ser canceladas. Esta classe fornece um mecanismo para cancelamento cooperativo entre threads, permitindo que uma thread notifique outras que uma operação deve ser cancelada.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## Métodos

| Método | Descrição |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | Construtor padrão. |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | Obtém se este token pode estar no estado cancelado. |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Obtém se o cancelamento foi solicitado para este token. |
| static [CancellationToken](./) [get_None](./get_none/)() | Retorna um valor [System::Threading::CancellationToken](./) vazio. |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | Registra uma callback que será invocada quando o cancelamento for solicitado. |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | Lança uma OperationCanceledException se o cancelamento for solicitado. |
## Observações

A [CancellationToken](./) só pode ser cancelado através de seu [CancellationTokenSource](../cancellationtokensource/) associado. 

## Veja Também

* Espaço de nomes [System::Threading](../)
* Biblioteca [Aspose.Slides](../../)