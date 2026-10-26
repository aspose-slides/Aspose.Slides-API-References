---
title: Enum
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce metodi che eseguono alcune operazioni sui valori di tipo enum. Si tratta di un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.
type: docs
weight: 1587
url: /it/system/enum/
---
## Struttura Enum

Fornisce metodi che eseguono alcune operazioni sui valori di tipo enum. Si tratta di un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di questo tipo in alcun modo.

```cpp
template<class E,class Guard>class Enum
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| E | Il tipo di enum i cui valori la classe gestisce |
| Guard | Argomento di tipo servizio il cui scopo è garantire che **E** sia un tipo enumerabile |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| static int [Compare](./compare/)(E, T) | Esegue il confronto aritmetico dei valori delle costanti di enumerazione specificate. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | Restituisce il nome della costante di enumerazione che ha il valore specificato. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | Restituisce il nome della costante di enumerazione che ha il valore specificato. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | Restituisce un array contenente i nomi di tutti i membri dell'enumerazione **E**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | Restituisce il tipo sottostante dell'enumerazione. |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | Restituisce un array contenente tutti i membri dell'enumerazione **E**. |
| static **bool** [HasFlag](./hasflag/)(E, E) | Determina se i bit specificati sono impostati in una rappresentazione binaria del valore enum specificato. |
| static **bool** [IsDefined](./isdefined/)(E) | Determina se il valore specificato è un membro del tipo di enumerazione **E**. |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | Determina se il valore specificato è un membro del tipo di enumerazione **T**. |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | Determina se il valore con il nome specificato è tra i membri dell'enum **E**. |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | Converte la stringa specificata in una costante enum equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | Prova a convertire la stringa specificata in una costante enum equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | Prova a convertire la stringa specificata in una costante enum equivalente. |
## Alias di tipo

| Typedef | Descrizione |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | Alias per il tipo sottostante dell'enum. |

## Vedi anche

* Namespace [System](../)
* Libreria [Aspose.Slides](../../)