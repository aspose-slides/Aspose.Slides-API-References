---
title: "System::Threading"
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 1002
url: /pt/system.threading/
---
## Classes

| Classe | Descrição |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | Evento para notificar a thread em espera que reinicia automaticamente. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo para funções como argumento. |
| [CancellationToken](./cancellationtoken/) | Propaga notificação de que as operações devem ser canceladas. Esta classe fornece um mecanismo para cancelamento cooperativo entre threads, permitindo que uma thread notifique outras de que uma operação deve ser cancelada. |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | Representa um registro para um callback de token de cancelamento. |
| [CancellationTokenSource](./cancellationtokensource/) | Uma origem de token de cancelamento que pode ser usada para disparar notificações de cancelamento. |
| [Details_SemaphoreFullException](./details_semaphorefullexception/) |  |
| [Details_SynchronizationLockException](./details_synchronizationlockexception/) |  |
| [Details_ThreadAbortException](./details_threadabortexception/) |  |
| [Details_ThreadInterruptedException](./details_threadinterruptedexception/) |  |
| [Details_ThreadStateException](./details_threadstateexception/) |  |
| [EventWaitHandle](./eventwaithandle/) | Evento que pode ser enviado para a thread em espera. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo para funções como argumento. |
| [Interlocked](./interlocked/) | Fornece API para operações thread-safe. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por qualquer meio. |
| [ManualResetEvent](./manualresetevent/) | Evento para notificar a thread em espera que não reinicia automaticamente. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo para funções como argumento. |
| [Monitor](./monitor/) | A classe [Monitor](./monitor/) fornece um mecanismo que sincroniza o acesso a objetos. |
| [Mutex](./mutex/) | [Mutex](./mutex/) implementação. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolver esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e usar esse ponteiro para passá-lo para funções como argumento. |
| [Semaphore](./semaphore/) | [Semaphore](./semaphore/) implementação. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolver esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e usar esse ponteiro para passá-lo para funções como argumento. |
| [SynchronizationContext](./synchronizationcontext/) | Fornece a funcionalidade básica para propagar um contexto de sincronização através de várias operações de sincronização. |
| [Thread](./thread/) | [Thread](./thread/) implementação. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolver esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e usar esse ponteiro para passá-lo para funções como argumento. |
| [ThreadPool](./threadpool/) | API de pool [Thread](./thread/) que permite enviar trabalhos para a fila a serem lidos por um pool de threads de trabalho. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por qualquer meio. |
| [ThreadPoolImpl](./threadpoolimpl/) | Dados internos do pool [Thread](./thread/). Este é um tipo singleton com gerenciamento de memória realizado por função(s) de acesso. Você nunca deve criar instâncias dele diretamente. |
| [Timer](./timer/) | Classe [Timer](./timer/) que executa item de trabalho em thread separada após atraso. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolver esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e usar esse ponteiro para passá-lo para funções como argumento. |
| [TimerQueue](./timerqueue/) | Fila que lida com objetos [Timer](./timer/). Esta é apenas uma implementação. Objetos [Timer](./timer/) se registram lá por si mesmos, você não precisa fazer isso para usá-los — use a API da classe [Timer](./timer/) em vez disso. Este é um tipo singleton com gerenciamento de memória realizado por função(s) de acesso. Você nunca deve criar instâncias dele diretamente. |
| [WaitHandle](./waithandle/) | Classe base de primitivo de espera. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolver esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e usar esse ponteiro para passá-lo para funções como argumento. |
## Estruturas

| Estrutura | Descrição |
| --- | --- |
| [Timeout](./timeout/) | Valores especiais de timeout [Threading](./). Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por qualquer meio. |
## Enumerações

| Enumeração | Descrição |
| --- | --- |
| [ApartmentState](./apartmentstate/) | Define o estado de apartamento da thread. |
| [EventResetMode](./eventresetmode/) | Indica como o estado do evento é reiniciado. |
| [ThreadState](./threadstate/) | Estado da thread. |
## Tipos Definidos

| Typedef | Descrição |
| --- | --- |
| [ThreadStateException](./threadstateexception/) |  |
| [SemaphoreFullException](./semaphorefullexception/) |  |
| [SynchronizationLockException](./synchronizationlockexception/) |  |
| [ThreadAbortException](./threadabortexception/) |  |
| [ThreadInterruptedException](./threadinterruptedexception/) |  |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | Função [Thread](./thread/) com um único parâmetro. |
| [ThreadStart](./threadstart/) | Função [Thread](./thread/) sem parâmetros. |
| [WaitCallback](./waitcallback/) | Item de callback a ser executado assim que houver um slot. |
| [TimerCallback](./timercallback/) | Função de callback a ser chamada pelo timer. |
| [wait_handle_t](./wait_handle_t/) | Tipo de handle. |