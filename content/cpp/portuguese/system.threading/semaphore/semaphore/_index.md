---
title: Semaphore()
second_title: Referência da API Aspose.Slides para C++
description: Cria semáforo sem nome.
type: docs
weight: 1
url: /pt/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) construtor


Cria semáforo sem nome.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| initialCount | int | Contagem inicial de entradas ativas. |
| maximumCount | int | Contagem máxima de entradas permitidas. |

## Semaphore::Semaphore(int, int, const String\&) construtor


Cria semáforo nomeado.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| initialCount | int | Contagem inicial de entradas ativas. |
| maximumCount | int | Contagem máxima de entradas permitidas. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) nome. |

## Semaphore::Semaphore(int, int, const String\&, bool\&) construtor


Cria semáforo nomeado.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| initialCount | int | Contagem inicial de entradas ativas. |
| maximumCount | int | Contagem máxima de entradas permitidas. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) nome. |
| createdNew | **bool**\& | Referência a variável que recebe true se o semáforo foi criado e false se um semáforo existente com o mesmo nome foi reutilizado |

## Veja Também

* Classe [Semaphore](../)
* Classe [String](../../../system/string/)
* Namespace [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)