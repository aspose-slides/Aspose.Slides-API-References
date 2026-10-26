---
title: TimerQueue
second_title: Aspose.Slides para Referência da API C++
description: Fila que lida com objetos Timer. Isto é apenas uma implementação. Objetos Timer registram-se lá por conta própria, você não precisa fazer isso para usá-los - use a API da classe Timer em vez disso. Este é um tipo singleton com gerenciamento de memória feito por função(s) de acesso. Você nunca deve criar instâncias dele diretamente.
type: docs
weight: 261
url: /pt/system.threading/timerqueue/
---
## TimerQueue classe


Fila que lida com objetos [Timer](../timer/). Isto é apenas uma implementação. Objetos [Timer](../timer/) registram-se lá por conta própria, você não precisa fazer isso para usá-los - use a API da classe [Timer](../timer/) em vez disso. Este é um tipo singleton com gerenciamento de memória feito por função(s) de acesso. Você nunca deve criar instâncias dele diretamente.

```cpp
class TimerQueue
```

## Métodos

| Método | Descrição |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | Registra o temporizador na fila. |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | Remove o temporizador da fila. |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | Singleton de implementação. |
| static void [JoinWorkerThread](./joinworkerthread/)() | Une a thread de trabalho. Aguarda indefinidamente se necessário. |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | Sem cópia. |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | Sem cópia. |

## Veja Também

* Namespace [System::Threading](../)
* Biblioteca [Aspose.Slides](../../)