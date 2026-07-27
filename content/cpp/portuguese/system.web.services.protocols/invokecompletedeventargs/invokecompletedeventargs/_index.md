---
title: InvokeCompletedEventArgs()
second_title: Referência da API Aspose.Slides for C++
description: Constrói uma nova instância.
type: docs
weight: 14
url: /pt/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) construtor

Constrói uma nova instância.

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | Qualquer erro que ocorreu durante uma operação assíncrona. |
| cancelled | **bool** | Um valor que indica se uma operação assíncrona foi cancelada. |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | O objeto de estado opcional fornecido pelo usuário passado para o método [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Uma coleção de resultados de operação assíncrona. |

## Ver Também

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Object](../../../system/object/)
* Classe [InvokeCompletedEventArgs](../)
* Espaço de nomes [System::Web::Services::Protocols](../../)
* Biblioteca [Aspose.Slides](../../../)