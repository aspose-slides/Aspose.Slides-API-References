---
title: FileVersionInfo
second_title: Riferimento API di Aspose.Slides per C++
description: "Fornisce informazioni sulla versione del file. Gli oggetti di questa classe dovrebbero essere allocati solo utilizzando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o guasti di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e usa questo puntatore per passarla alle funzioni come argomento."
type: docs
weight: 1
url: /it/system.diagnostics/fileversioninfo/
---
## FileVersionInfo classe

Fornisce informazioni sulla versione del file. Gli oggetti di questa classe dovrebbero essere allocati solo utilizzando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o utilizzando l'operatore new, poiché ciò provocherà errori di runtime e/o guasti di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e utilizza questo puntatore per passarlo alle funzioni come argomento.

```cpp
class FileVersionInfo
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [String](../../system/string/) [get_ProductVersion](./get_productversion/)() const | Ottiene il campo della versione del prodotto. |
| static [SharedPtr](../../system/sharedptr/)\<[System::Diagnostics::FileVersionInfo](./)\> [GetVersionInfo](./getversioninfo/)(const [String](../../system/string/)\&) | Ottiene le informazioni sulla versione del file; non implementato. |

## Vedi anche

* Spazio dei nomi [System::Diagnostics](../)
* Libreria [Aspose.Slides](../../)