---
title: Join()
second_title: Referência da API Aspose.Slides para C++
description: Une o thread gerenciado. Realiza espera ilimitada se necessário.
type: docs
weight: 196
url: /pt/system.threading/thread/join/
---
## Thread::Join() método

Une o thread gerenciado. Realiza espera ilimitada se necessário.

```cpp
void System::Threading::Thread::Join()
```

## Thread::Join(int) método

Une o thread gerenciado. Realiza espera limitada.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| millisecondsTimeout | int | Tempo limite de espera em milissegundos. |

### Valor de Retorno

True se o thread foi unido com sucesso, false se o tempo limite foi excedido.

## Thread::Join(TimeSpan) método

Une o thread gerenciado. Realiza espera limitada.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Um [TimeSpan](../../../system/timespan/) definido para a quantidade de tempo a aguardar a finalização do thread. |

### Valor de Retorno

True se o thread foi unido com sucesso, false se o tempo limite foi excedido.

## Veja Também

* Classe [Thread](../)
* Classe [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)