---
title: AsyncCompletedEventArgs()
second_title: Referência da API Aspose.Slides for C++
description: Construtor.
type: docs
weight: 1
url: /pt/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() construtor


Construtor.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) construtor


Inicializa uma nova instância da classe [System.ComponentModel.AsyncCompletedEventArgs](../).

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | Qualquer erro que ocorreu durante a operação assíncrona. |
| canceled | **bool** | Um valor que indica se a operação assíncrona foi cancelada. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | O objeto de estado opcional fornecido pelo usuário passado para o método [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |

## Veja Também

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [AsyncCompletedEventArgs](../)
* Classe [Object](../../../system/object/)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)