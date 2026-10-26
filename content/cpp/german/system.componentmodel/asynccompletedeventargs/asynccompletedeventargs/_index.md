---
title: AsyncCompletedEventArgs()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruktor.
type: docs
weight: 1
url: /de/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() Konstruktor

Konstruktor.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) Konstruktor

Initialisiert eine neue Instanz der Klasse [System.ComponentModel.AsyncCompletedEventArgs](../).

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | Jeder Fehler, der während des asynchronen Vorgangs aufgetreten ist. |
| canceled | **bool** | Ein Wert, der angibt, ob der asynchrone Vorgang abgebrochen wurde. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Das optionale, vom Benutzer bereitgestellte Zustandsobjekt, das an die Methode [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) übergeben wird. |

## Siehe auch

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [AsyncCompletedEventArgs](../)
* Klasse [Object](../../../system/object/)
* Namensraum [System::ComponentModel](../../)
* Bibliothek [Aspose.Slides](../../../)