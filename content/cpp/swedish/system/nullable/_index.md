---
title: Nullable
second_title: Aspose.Slides för C++ API-referens
description: Framåtriktad deklaration.
type: docs
weight: 1106
url: /sv/system/nullable/
---
## Nullabel klass

Forward declaration.

```cpp
template<typename T>class Nullable
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Den underliggande värdetypen som utökas av klassen [Nullable](./). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | Bestämmer om värdet som representeras av det aktuella objektet är lika med värdet som representeras av det angivna [Nullable](./)-objektet. |
| **bool** [get_HasValue](./get_hasvalue/)() const | Bestämmer om det aktuella objektet representerar något värde. |
| T [get_Value](./get_value/)() const | Returnerar en kopia av värdet som representeras av det aktuella objektet. |
| int [GetHashCode](./gethashcode/)() const | Returnerar en hash-kod för det aktuella objektet. |
| T [GetValueOrDefault](./getvalueordefault/)(T) | Returnerar värdet som representeras av det aktuella objektet eller det angivna värdet om värdet som representeras av det aktuella objektet är null. |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | Bestämmer om det aktuella objektet representerar ett null-värde. |
|  [Nullable](./nullable/)() | Konstruerar en instans som representerar ett null-värde. |
|  [Nullable](./nullable/)(std::nullptr_t) | Konstruerar en instans som representerar null. |
|  [Nullable](./nullable/)(const T1\&) | Konstruerar en instans av [Nullable](./) klass som representerar det angivna värdet konverterat (om nödvändigt) till värdet av den underliggande typen T. |
|  [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | Konstruerar en instans som representerar ett värde som representeras av det angivna [Nullable](./)-objektet. Det angivna nullabla objektet kan representera ett värde av en annan typ än den underliggande typen för den konstruerade instansen, i så fall konverteras det representerade värdet till en värde av typ T. |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | Hjälpfunktion för att kontrollera om både detta och **other** inte är null och anropa ett lambda-uttryck i så fall. Används i implementationer. |
|  [operator const T &](./operator_const_t__and/)() const | Returnerar en konstant referens till värdet som representeras av det aktuella objektet. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Bestämmer om värdet som representeras av det aktuella objektet inte är null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | Bestämmer om värdet som representeras av det aktuella objektet inte är lika med det angivna värdet. |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | Bestämmer om värdet som representeras av det aktuella objektet inte är lika med värdet som representeras av det angivna [Nullable](./)-objektet. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | Applicerar [operator&=()](./operator_and_equal/) på värdet som representeras av det aktuella objektet med det angivna värdet som högersidig argument. |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | Returnerar en standardkonstrukt instans av Nullable<T>-klassen. |
| auto [operator+](./operator_plus/)(const T1\&) const | Summerar nullabla och icke-nullabla värden. |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | Summerar nullabla värden. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | Återställer det aktuella objektet så att det representerar ett null-värde. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | Applicerar [operator+=()](./operator_plus_equal/) på värdet som representeras av det aktuella objektet med det angivna värdet som högersidig argument. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | Applicerar [operator+=()](./operator_plus_equal/) på värdet som representeras av det aktuella objektet med värdet som representeras av det angivna [Nullable](./)-objektet som högersidig argument. |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | Subtraherar nullabla och null-pekade värden. |
| auto [operator-](./operator_minus/)(const T1\&) const | Subtraherar nullabla och icke-nullabla värden. |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | Subtraherar nullabla värden. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | Returnerar en instans av [Nullable](./) klass som representerar ett null-värde. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | Applicerar [operator-=()](./operator_minus_equal/) på värdet som representeras av det aktuella objektet med det angivna värdet som högersidig argument. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | Applicerar [operator-=()](./operator_minus_equal/) på värdet som representeras av det aktuella objektet med värdet som representeras av det angivna [Nullable](./)-objektet som högersidig argument. |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | Returnerar alltid false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | Bestämmer om värdet som representeras av det aktuella objektet är mindre än det angivna värdet genom att applicera [operator<()](./operator_less/) på dessa värden. |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | Bestämmer om värdet som representeras av det aktuella objektet är mindre än värdet som representeras av det angivna [Nullable](./)-objektet genom att applicera [operator<()](./operator_less/) på dessa värden. |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | Returnerar alltid false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | Bestämmer om värdet som representeras av det aktuella objektet är mindre eller lika med det angivna värdet genom att applicera [operator<=()](./operator_less_equal/) på dessa värden. |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | Bestämmer om värdet som representeras av det aktuella objektet är mindre eller lika med värdet som representeras av det angivna [Nullable](./)-objektet genom att applicera [operator<=()](./operator_less_equal/) på dessa värden. |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | Tilldelar null till det aktuella objektet. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | Ersätter objektets för närvarande representerade värde med det angivna. |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | Ersätter objektets för närvarande representerade värde med det angivna. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Bestämmer om värdet som representeras av det aktuella objektet är null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | Bestämmer om värdet som representeras av det aktuella objektet är lika med det angivna värdet. |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | Bestämmer om värdet som representeras av det aktuella objektet är lika med värdet som representeras av det angivna [Nullable](./)-objektet. |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | Returnerar alltid false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | Bestämmer om värdet som representeras av det aktuella objektet är större än det angivna värdet genom att applicera [operator>()](./operator_greater/) på dessa värden. |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | Bestämmer om värdet som representeras av det aktuella objektet är större än värdet som representeras av det angivna [Nullable](./)-objektet genom att applicera [operator>()](./operator_greater/) på dessa värden. |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | Returnerar alltid false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | Bestämmer om värdet som representeras av det aktuella objektet är större eller lika med värdet som representeras av det angivna objektet genom att applicera [operator>=()](./operator_greater_equal/) på dessa värden. |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | Bestämmer om värdet som representeras av det aktuella objektet är större eller lika med värdet som representeras av det angivna [Nullable](./)-objektet genom att applicera [operator>=()](./operator_greater_equal/) på dessa värden. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | Applicerar [operator|=()](./operator_or_equal/) på värdet som representeras av det aktuella objektet med det angivna värdet som högersidig argument. |
| void [reset](./reset/)() | Sätter det för närvarande representerade värdet till null. |
| void [set_Value](./set_value/)(const T\&) | Sätter ett nytt värde till det nullabla objektet. |
| [String](../string/) [ToString](./tostring/)() const | Konverterar värdet som representeras av det aktuella objektet till sträng. |
## Typdefinitioner

| Typedef | Beskrivning |
| --- | --- |
| [ValueType](./valuetype/) | Ett alias för en typ av värdet som representeras av denna klass. |
## Anmärkningar

Representerar ett värde av den angivna typen som kan tilldelas null. Denna typ bör allokeras på stacken och passeras till funktioner som värde eller som referens. Använd aldrig [System::SmartPtr](../smartptr/) klass för att hantera objekt av denna typ.

## Se också

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)