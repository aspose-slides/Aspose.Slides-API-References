---
title: ThreadPoolImpl
second_title: Aspose.Slides para C++ Referência da API
description: Dados internos do pool de threads. Este é um tipo singleton com gerenciamento de memória realizado por função(s) de acesso. Você nunca deve criar instâncias dele diretamente.
type: docs
weight: 235
url: /pt/system.threading/threadpoolimpl/
---
## ThreadPoolImpl classe


[Thread](../thread/) dados internos do pool. Este é um tipo singleton com gerenciamento de memória realizado por função(s) de acesso. Você nunca deve criar instâncias dele diretamente.

```cpp
class ThreadPoolImpl
```

## Métodos

| Method | Description |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Obtém o número de threads disponíveis. |
| static **bool**\& [GetInitialized](./getinitialized/)() | Obtém o singleton de estado de inicialização. |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Obtém o número máximo de threads concorrentes. |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | Obtém o número mínimo de threads sendo criadas pelo pool. |
| void [JoinAll](./joinall/)() | Une todas as threads de propriedade. Aguarda indefinidamente. |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Adiciona item de trabalho à fila. |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | Define o número de threads de propriedade do pool. |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | Define o número mínimo de threads de propriedade do pool. |
|  [ThreadPoolImpl](./threadpoolimpl/)() | Construtor. |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | Destrutor. Une todas as threads se ainda não foram terminadas. |
## Veja Também

* Espaço de nomes [System::Threading](../)
* Library [Aspose.Slides](../../)