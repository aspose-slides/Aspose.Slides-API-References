---
title: Build()
second_title: Aspose.Slides voor C++ API-referentie
description: Bouw een object met directe eigendom.
type: docs
weight: 2289
url: /nl/system/build/
---
## System::Build(Args\&&...) functie


Bouw een object met directe eigendom.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van object om te bouwen |
| Args | Argumenttypen voor objectconstructie |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| args | Args\&&... | Argumenten om door te geven aan objectconstructor |

### Retourwaarde

ObjectBuilder geconfigureerd voor directe objectconstructie
## Opmerkingen



[Object](../object/) constructie moet worden afgerond met [Get()](../get/) aanroep 

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)