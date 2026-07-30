---
title: Nullable
second_title: Riferimento API di Aspose.Slides per C++
description: Dichiarazione anticipata.
type: docs
weight: 1106
url: /it/system/nullable/
---
## Classe Nullable

Forward declaration.

```cpp
template<typename T>class Nullable
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di valore sottostante che è esteso dalla classe [Nullable](./) |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | Determina se il valore rappresentato dall'oggetto corrente è uguale al valore rappresentato dall'oggetto [Nullable](./) specificato. |
| **bool** [get_HasValue](./get_hasvalue/)() const | Determina se l'oggetto corrente rappresenta un valore qualsiasi. |
| T [get_Value](./get_value/)() const | Restituisce una copia del valore rappresentato dall'oggetto corrente. |
| int [GetHashCode](./gethashcode/)() const | Restituisce un codice hash per l'oggetto corrente. |
| T [GetValueOrDefault](./getvalueordefault/)(T) | Restituisce il valore rappresentato dall'oggetto corrente o il valore specificato se il valore rappresentato dall'oggetto corrente è nullo. |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | Determina se l'oggetto corrente rappresenta un valore nullo. |
| [Nullable](./nullable/)() | Costruisce un'istanza che rappresenta un valore nullo. |
| [Nullable](./nullable/)(std::nullptr_t) | Costruisce un'istanza che rappresenta null. |
| [Nullable](./nullable/)(const T1\&) | Costruisce un'istanza della classe [Nullable](./) che rappresenta il valore specificato convertito (se necessario) al valore del tipo sottostante T. |
| [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | Costruisce un'istanza che rappresenta un valore rappresentato dall'oggetto [Nullable](./) specificato. L'oggetto nullable specificato può rappresentare un valore di tipo diverso rispetto al tipo sottostante dell'istanza costruita, nel qual caso il valore rappresentato è convertito a un valore di tipo T. |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | Funzione di supporto per verificare se questo e **other** non sono entrambi nulli e chiamare una lambda in tal caso. Usata nelle implementazioni. |
| [operator const T &](./operator_const_t__and/)() const | Restituisce un riferimento costante al valore rappresentato dall'oggetto corrente. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Determina se il valore rappresentato dall'oggetto corrente non è nullo. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | Determina se il valore rappresentato dall'oggetto corrente non è uguale al valore specificato. |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | Determina se il valore rappresentato dall'oggetto corrente non è uguale al valore rappresentato dall'oggetto [Nullable](./) specificato. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | Applica [operator&=()](./operator_and_equal/) al valore rappresentato dall'oggetto corrente usando il valore specificato come argomento a destra. |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | Restituisce un'istanza costruita di default della classe Nullable<T>. |
| auto [operator+](./operator_plus/)(const T1\&) const | Somma valori nullable e non nullable. |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | Somma valori nullable. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | Reimposta l'oggetto corrente in modo che rappresenti un valore nullo. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | Applica [operator+=()](./operator_plus_equal/) al valore rappresentato dall'oggetto corrente usando il valore specificato come argomento a destra. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | Applica [operator+=()](./operator_plus_equal/) al valore rappresentato dall'oggetto corrente usando il valore rappresentato dall'oggetto [Nullable](./) specificato come argomento a destra. |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | Sottrae valori nullable e valori puntati a null. |
| auto [operator-](./operator_minus/)(const T1\&) const | Sottrae valori nullable e non nullable. |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | Sottrae valori nullable. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | Restituisce un'istanza della classe [Nullable](./) che rappresenta un valore nullo. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | Applica [operator-=()](./operator_minus_equal/) al valore rappresentato dall'oggetto corrente usando il valore specificato come argomento a destra. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | Applica [operator-=()](./operator_minus_equal/) al valore rappresentato dall'oggetto corrente usando il valore rappresentato dall'oggetto [Nullable](./) specificato come argomento a destra. |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | Restituisce sempre false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | Determina se il valore rappresentato dall'oggetto corrente è minore del valore specificato applicando [operator<()](./operator_less/) a questi valori. |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | Determina se il valore rappresentato dall'oggetto corrente è minore del valore rappresentato dall'oggetto [Nullable](./) specificato applicando [operator<()](./operator_less/) a questi valori. |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | Restituisce sempre false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | Determina se il valore rappresentato dall'oggetto corrente è minore o uguale al valore specificato applicando [operator<=()](./operator_less_equal/) a questi valori. |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | Determina se il valore rappresentato dall'oggetto corrente è minore o uguale al valore rappresentato dall'oggetto [Nullable](./) specificato applicando [operator<=()](./operator_less_equal/) a questi valori. |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | Assegna un null all'oggetto corrente. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | Sostituisce il valore attualmente rappresentato dall'oggetto con quello specificato. |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | Sostituisce il valore attualmente rappresentato dall'oggetto con quello specificato. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Determina se il valore rappresentato dall'oggetto corrente è nullo. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | Determina se il valore rappresentato dall'oggetto corrente è uguale al valore specificato. |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | Determina se il valore rappresentato dall'oggetto corrente è uguale al valore rappresentato dall'oggetto [Nullable](./) specificato. |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | Restituisce sempre false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | Determina se il valore rappresentato dall'oggetto corrente è maggiore del valore specificato applicando [operator>()](./operator_greater/) a questi valori. |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | Determina se il valore rappresentato dall'oggetto corrente è maggiore del valore rappresentato dall'oggetto [Nullable](./) specificato applicando [operator>()](./operator_greater/) a questi valori. |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | Restituisce sempre false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | Determina se il valore rappresentato dall'oggetto corrente è maggiore o uguale al valore rappresentato dall'oggetto specificato applicando [operator>=()](./operator_greater_equal/) a questi valori. |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | Determina se il valore rappresentato dall'oggetto corrente è maggiore o uguale al valore rappresentato dall'oggetto [Nullable](./) specificato applicando [operator>=()](./operator_greater_equal/) a questi valori. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | Applica [operator|=()](./operator_or_equal/) al valore rappresentato dall'oggetto corrente usando il valore specificato come argomento a destra. |
| void [reset](./reset/)() | Imposta il valore attualmente rappresentato a null. |
| void [set_Value](./set_value/)(const T\&) | Imposta un nuovo valore all'oggetto nullable. |
| [String](../string/) [ToString](./tostring/)() const | Converte il valore rappresentato dall'oggetto corrente in stringa. |

## Typedef

| Typedef | Descrizione |
| --- | --- |
| [ValueType](./valuetype/) | Un alias per un tipo del valore rappresentato da questa classe. |

## Osservazioni

Rappresenta un valore del tipo specificato che può essere assegnato a null. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe [System::SmartPtr](../smartptr/) per gestire oggetti di questo tipo.

## Vedi anche

* Namespace [System](../)
* Libreria [Aspose.Slides](../../)