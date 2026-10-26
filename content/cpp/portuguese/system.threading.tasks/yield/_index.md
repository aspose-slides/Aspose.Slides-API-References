---
title: Yield()
second_title: Referência da API Aspose.Slides for C++
description: Cria uma tarefa aguardável que, de forma assíncrona, devolve o controle ao contexto atual quando aguardada.
type: docs
weight: 222
url: /pt/system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield() função

Cria uma tarefa aguardável que, de forma assíncrona, devolve o controle ao contexto atual quando aguardada.

```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```

### Valor de Retorno

Um YieldAwaitable que pode ser aguardado para ceder o controle.

## Observações

Este método é útil para forçar um método assíncrono a ceder o controle, permitindo que outros trabalhos pendentes sejam processados antes de continuar.

## Veja Também

* Classe [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* Espaço de nomes [System::Threading::Tasks](../)
* Biblioteca [Aspose.Slides](../../)