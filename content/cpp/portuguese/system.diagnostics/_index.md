---
title: "System::Diagnostics"
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 469
url: /pt/system.diagnostics/
---
## Classes

| Classe | Descrição |
| --- | --- |
| [FileVersionInfo](./fileversioninfo/) | Fornece informações sobre a versão do arquivo. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [PerformanceCounter](./performancecounter/) | Classe fictícia para compilação de código traduzido que usa PerformanceCounter. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [Process](./process/) | Encapsula informações e manipulação de processos. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [ProcessStartInfo](./processstartinfo/) | Descreve os parâmetros de inicialização do processo. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [StackFrame](./stackframe/) | Obtém informações sobre um único quadro de pilha. Apenas MSVS. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [StackTrace](./stacktrace/) | Coleção de quadros de pilha. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [Stopwatch](./stopwatch/) | Permite a medição de tempo. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [TraceListener](./tracelistener/) | Interface para reagir a informações de depuração e rastreamento. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |

## Estruturas

| Estrutura | Descrição |
| --- | --- |
| [Debug](./debug/) | Coleção de métodos de depuração que permitem enviar informações de depuração a ouvintes registrados. Todas as funções de saída funcionam apenas em [Debug](./debug/). Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por quaisquer meios. |
| [Debugger](./debugger/) | Interface [Debugger](./debugger/). Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por quaisquer meios. |
| [Trace](./trace/) | Fornece interface para acessar o rastreamento do depurador (se houver). Funciona apenas no modo [Debug](./debug/). Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por quaisquer meios. |

## Enumerações

| Enumeração | Descrição |
| --- | --- |
| [ProcessWindowStyle](./processwindowstyle/) | Estilo da janela do processo. |
| [TraceEventType](./traceeventtype/) | Identifica o tipo de evento que causou o rastreamento. |
| [TraceLevel](./tracelevel/) | Especifica quais mensagens devem ser emitidas para as classes [System.Diagnostics.Debug](./debug/), [System.Diagnostics.Trace](./trace/) e System.Diagnostics.TraceSwitch. |

## Tipos Definidos

| Tipo Definido | Descrição |
| --- | --- |
| [StopwatchPtr](./stopwatchptr/) | Tipo ponteiro. |