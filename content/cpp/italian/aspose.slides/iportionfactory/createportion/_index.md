---
title: CreatePortion()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una porzione di testo vuota.
type: docs
weight: 1
url: /it/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() metodo


Crea una porzione di testo vuota.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```


### Valore di ritorno

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) metodo


Crea una porzione di testo dalla stringa specificata.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | Stringa. |

### Valore di ritorno

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) metodo


Crea una porzione utilizzando i dati di una porzione specificata.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Una porzione da usare. |

### Valore di ritorno

[Portion](../../portion/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPortion](../../iportion/)
* Classe [IPortionFactory](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)