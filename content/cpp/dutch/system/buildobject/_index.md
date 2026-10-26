---
title: BuildObject()
second_title: Aspose.Slides voor C++ API-referentie
description: Bouw een object met gedeeld eigendom.
type: docs
weight: 2250
url: /nl/system/buildobject/
---
## System::BuildObject(Args\&&...) functie


Bouw een object met gedeeld eigendom.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van object om te bouwen |
| Args | Argumenttypen voor objectconstructie |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| args | Args\&&... | Argumenten om door te geven aan de objectconstructor |

### Retourwaarde

ObjectBuilder geconfigureerd voor constructie van gedeelde pointer
## Opmerkingen



Maakt een SharedPtr<T> aan en retourneert een builder ervoor 
[Object](../object/) constructie moet worden voltooid met [Get()](../get/) aanroep 

## Zie ook

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)