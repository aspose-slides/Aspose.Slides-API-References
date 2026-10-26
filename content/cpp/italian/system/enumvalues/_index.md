---
title: EnumValues
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce informazioni meta sui costanti di enumerazione del tipo enum E.
type: docs
weight: 794
url: /it/system/enumvalues/
---
## EnumValues classe

Fornisce informazioni meta sui costanti di enumerazione del tipo enum **E**.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| E | Il tipo di enumerazione |

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [EnumValues](./enumvalues/)() | Crea un'istanza. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | Restituisce un array contenente tutti i nomi dell'enumerazione **E**. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | Recupera un array dei nomi delle costanti in una enumerazione specificata. |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | Restituisce il tipo sottostante dell'enumerazione specificata. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Restituisce il tipo sottostante dell'enumerazione specificata. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | Restituisce il valore boxed della costante enum con il nome specificato. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | Restituisce il valore boxed della costante enum con il valore specificato. |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | Restituisce un array contenente tutti i valori dell'enumerazione **E**. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | Restituisce un array contenente tutti i valori del tipo di enumerazione specificato. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Restituisce un oggetto che rappresenta il valore di una costante di enumerazione del tipo di enumerazione specificato con il nome specificato. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Converte il valore intero senza segno a 64 bit specificato in un membro dell'enumerazione. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Converte l'oggetto specificato con un valore intero in un membro dell'enumerazione. |
| virtual  [~EnumValues](./~enumvalues/)() | Distruttore. |

## Vedi anche

* Classe [EnumValuesBase](../enumvaluesbase/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)