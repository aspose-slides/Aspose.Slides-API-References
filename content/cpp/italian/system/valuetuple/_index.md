---
title: ValueTuple
second_title: Riferimento API Aspose.Slides per C++
description: Classe che rappresenta una struttura dati ValueTuple.
type: docs
weight: 1444
url: /it/system/valuetuple/
---
## ValueTuple classe

Classe che rappresenta una struttura dati [ValueTuple](./).

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | Determina se gli oggetti corrente e quello specificato sono identici. |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() | Ottiene il riferimento al valore del componente dell'oggetto [ValueTuple](./). |
| const std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() const | Ottiene il valore del componente dell'oggetto [ValueTuple](./). |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Decompone l'oggetto in questa tupla di valori. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Restituisce un riferimento all'oggetto [TypeInfo](../typeinfo/) che rappresenta le informazioni sul tipo della classe [ValueTuple](./). |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) | Costruisce un oggetto tupla. |

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)