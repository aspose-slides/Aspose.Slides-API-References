---
title: CreatePortion()
second_title: Aspose.Slides per C++ Riferimento API
description: Crea una porzione di testo vuota.
type: docs
weight: 1
url: /it/aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() metodo

Crea una porzione di testo vuota.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```

### Valore di ritorno

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) metodo

Crea una porzione di testo dalla stringa specificata.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | Stringa. |

### Valore di ritorno

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) metodo

Crea una porzione utilizzando i dati di una porzione specificata.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Una porzione da utilizzare. |

### Valore di ritorno

[Portion](../../portion/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPortion](../../iportion/)
* Classe [PortionFactory](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)