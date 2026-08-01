---
title: InvokeCompletedEventArgs()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een nieuw exemplaar.
type: docs
weight: 14
url: /nl/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) constructor

Maakt een nieuw exemplaar.

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | Elke fout die zich heeft voorgedaan tijdens een asynchrone bewerking. |
| cancelled | **bool** | Een waarde die aangeeft of een asynchrone bewerking is geannuleerd. |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Het optionele door de gebruiker geleverde statusobject dat wordt doorgegeven aan de [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) methode. |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Een verzameling resultaten van asynchrone bewerkingen. |

## Zie ook

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Object](../../../system/object/)
* Klasse [InvokeCompletedEventArgs](../)
* Naamruimte [System::Web::Services::Protocols](../../)
* Bibliotheek [Aspose.Slides](../../../)