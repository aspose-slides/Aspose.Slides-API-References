---
title: EnumValuesBase
second_title: Riferimento API di Aspose.Slides per C++
description: Una classe base per una classe che rappresenta le informazioni meta di un tipo di enumerazione.
type: docs
weight: 807
url: /it/system/enumvaluesbase/
---
## EnumValuesBase classe

Una classe base per una classe che rappresenta le informazioni meta di un tipo di enumerazione.

```cpp
class EnumValuesBase
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | Recupera un array dei nomi delle costanti in una enumerazione specificata. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Restituisce il tipo sottostante dell'enumerazione specificata. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | Restituisce un array contenente tutti i valori del tipo di enumerazione specificato. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Restituisce un oggetto che rappresenta un valore della costante di enumerazione del tipo di enumerazione specificato con il nome specificato. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Converte il valore intero non firmato a 64 bit specificato in un membro dell'enumerazione. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Converte l'oggetto specificato con un valore intero in un membro dell'enumerazione. |
## Vedi anche

* Namespace [System](../)
* Libreria [Aspose.Slides](../../)