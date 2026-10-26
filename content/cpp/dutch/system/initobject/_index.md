---
title: InitObject()
second_title: Aspose.Slides voor C++ API-referentie
description: Start de initialisatie van een object met gedeeld eigendom.
type: docs
weight: 2263
url: /nl/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) functie

Start de initialisatie van een object met gedeeld eigendom.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van object om te initialiseren |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) om te initialiseren |

### Retourwaarde

ObjectBuilder geconfigureerd voor constructie van gedeelde pointer

## Opmerkingen

[Object](../object/) initialisatie moet worden voltooid met [Get()](../get/) aanroep 

## Zie ook

* Typedef [SharedPtr](../sharedptr/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)