---
title: AsyncCompletedEventArgs()
second_title: Aspose.Slides voor C++ API-referentie
description: Constructor.
type: docs
weight: 1
url: /nl/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() constructor


Constructor.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) constructor


Initialiseert een nieuw exemplaar van de [System.ComponentModel.AsyncCompletedEventArgs](../) klasse.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | Elke fout die zich heeft voorgedaan tijdens de asynchrone bewerking. |
| canceled | **bool** | Een waarde die aangeeft of de asynchrone bewerking is geannuleerd. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Het optionele door de gebruiker geleverde statusobject dat wordt doorgegeven aan de [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) methode. |

## Zie ook

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [AsyncCompletedEventArgs](../)
* Class [Object](../../../system/object/)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)