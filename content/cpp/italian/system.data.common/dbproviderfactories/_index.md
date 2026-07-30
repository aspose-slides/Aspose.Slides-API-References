---
title: DbProviderFactories
second_title: Riferimento API Aspose.Slides per C++
description: "API per ottenere le factory del provider DB. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o errori di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e usa questo puntatore per passarla alle funzioni come argomento."
type: docs
weight: 53
url: /it/system.data.common/dbproviderfactories/
---
## DbProviderFactories classe

API per ottenere le factory del provider DB. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai istanze di questo tipo nello stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o errori di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarla alle funzioni come argomento.

```cpp
class DbProviderFactories
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[DbProviderFactory](../dbproviderfactory/)\> [GetFactory](./getfactory/)(const [String](../../system/string/)\&) | Ottiene la factory del provider DB per nome. |

## Vedi anche

* Spazio dei nomi [System::Data::Common](../)
* Libreria [Aspose.Slides](../../)