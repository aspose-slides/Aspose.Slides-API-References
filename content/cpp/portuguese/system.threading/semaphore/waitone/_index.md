---
title: WaitOne()
second_title: Aspose.Slides para C++ Referência da API
description: Bloqueia o semáforo. Realiza espera ilimitada, se necessário.
type: docs
weight: 40
url: /pt/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() método


Bloqueia o semáforo. Realiza espera ilimitada, se necessário.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```


### Valor de Retorno

Sempre retorna true, pois não retorna até que o semáforo esteja bloqueado.

## Semaphore::WaitOne(int) método


Bloqueia o semáforo. Realiza espera, se necessário.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| millisecondsTimeout | int | Tempo de espera em milissegundos. |

### Valor de Retorno

Retorna true se o semáforo foi bloqueado ou false se o tempo limite foi excedido.

## Veja Também

* Classe [Semaphore](../)
* Namespace [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)