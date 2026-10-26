---
title: Nullable
second_title: Aspose.Slides pro C++ API Reference
description: Předběžná deklarace.
type: docs
weight: 1106
url: /cs/system/nullable/
---
## Nullable třída

Forward deklarace.

```cpp
template<typename T>class Nullable
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Základní typ hodnoty, který je rozšířen třídou [Nullable](./) |

## Metody

| Metoda | Popis |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | Určuje, zda je hodnota reprezentovaná aktuálním objektem rovna hodnotě reprezentované zadaným objektem [Nullable](./). |
| **bool** [get_HasValue](./get_hasvalue/)() const | Určuje, zda aktuální objekt představuje nějakou hodnotu. |
| T [get_Value](./get_value/)() const | Vrací kopii hodnoty reprezentované aktuálním objektem. |
| int [GetHashCode](./gethashcode/)() const | Vrací hash kód pro aktuální objekt. |
| T [GetValueOrDefault](./getvalueordefault/)(T) | Vrací hodnotu reprezentovanou aktuálním objektem nebo zadanou hodnotu, pokud je hodnota reprezentovaná aktuálním objektem null. |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | Určuje, zda aktuální objekt představuje null-hodnotu. |
| [Nullable](./nullable/)() | Vytvoří instanci, která představuje null-hodnotu. |
| [Nullable](./nullable/)(std::nullptr_t) | Vytvoří instanci, která představuje null. |
| [Nullable](./nullable/)(const T1\&) | Vytvoří instanci třídy [Nullable](./), která představuje zadanou hodnotu převedenou (je-li to nutné) na hodnotu základního typu T. |
| [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | Vytvoří instanci, která představuje hodnotu reprezentovanou zadaným objektem [Nullable](./). Zadaný nullable objekt může představovat hodnotu jiného typu než základní typ vytvářené instance, v takovém případě je reprezentovaná hodnota převedena na typ T. |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | Pomocná funkce pro kontrolu, zda jsou tento a **other** oba nenulové, a v takovém případě zavolá lambda výraz. Použito v implementation.s. |
| [operator const T &](./operator_const_t__and/)() const | Vrací konstantní referenci na hodnotu reprezentovanou aktuálním objektem. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Určuje, zda hodnota reprezentovaná aktuálním objektem není null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | Určuje, zda hodnota reprezentovaná aktuálním objektem není rovna zadané hodnotě. |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | Určuje, zda hodnota reprezentovaná aktuálním objektem není rovna hodnotě reprezentované zadaným objektem [Nullable](./). |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | Aplikuje [operator&=()](./operator_and_equal/) na hodnotu reprezentovanou aktuálním objektem s použitím zadané hodnoty jako pravého argumentu. |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | Vrací výchozí konstrukci instance třídy Nullable<T>. |
| auto [operator+](./operator_plus/)(const T1\&) const | Sčítá nullable a ne-null hodnoty. |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | Sčítá nullable hodnoty. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | Resetuje aktuální objekt tak, aby představoval null-hodnotu. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | Aplikuje [operator+=()](./operator_plus_equal/) na hodnotu reprezentovanou aktuálním objektem s použitím zadané hodnoty jako pravého argumentu. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | Aplikuje [operator+=()](./operator_plus_equal/) na hodnotu reprezentovanou aktuálním objektem s použitím hodnoty reprezentované zadaným objektem [Nullable](./) jako pravého argumentu. |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | Odčítá nullable a null-směřované hodnoty. |
| auto [operator-](./operator_minus/)(const T1\&) const | Odčítá nullable a ne-null hodnoty. |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | Odčítá nullable hodnoty. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | Vrací instanci třídy [Nullable](./), která představuje null-hodnotu. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | Aplikuje [operator-=()](./operator_minus_equal/) na hodnotu reprezentovanou aktuálním objektem s použitím zadané hodnoty jako pravého argumentu. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | Aplikuje [operator-=()](./operator_minus_equal/) na hodnotu reprezentovanou aktuálním objektem s použitím hodnoty reprezentované zadaným objektem [Nullable](./) jako pravého argumentu. |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | Vždy vrací false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | Určuje, zda je hodnota reprezentovaná aktuálním objektem menší než zadaná hodnota aplikací [operator<()](./operator_less/) na tyto hodnoty. |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | Určuje, zda je hodnota reprezentovaná aktuálním objektem menší než hodnota reprezentovaná zadaným objektem [Nullable](./) aplikací [operator<()](./operator_less/) na tyto hodnoty. |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | Vždy vrací false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | Určuje, zda je hodnota reprezentovaná aktuálním objektem menší nebo rovna zadané hodnotě aplikací [operator<=()](./operator_less_equal/) na tyto hodnoty. |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | Určuje, zda je hodnota reprezentovaná aktuálním objektem menší nebo rovna hodnotě reprezentované zadaným objektem [Nullable](./) aplikací [operator<=()](./operator_less_equal/) na tyto hodnoty. |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | Přiřadí null aktuálnímu objektu. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | Nahrazuje aktuálně reprezentovanou hodnotu objektu zadanou hodnotou. |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | Nahrazuje aktuálně reprezentovanou hodnotu objektu zadanou hodnotou. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Určuje, zda je hodnota reprezentovaná aktuálním objektem null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | Určuje, zda je hodnota reprezentovaná aktuálním objektem rovna zadané hodnotě. |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | Určuje, zda je hodnota reprezentovaná aktuálním objektem rovna hodnotě reprezentované zadaným objektem [Nullable](./). |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | Vždy vrací false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | Určuje, zda je hodnota reprezentovaná aktuálním objektem větší než zadaná hodnota aplikací [operator>()](./operator_greater/) na tyto hodnoty. |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | Určuje, zda je hodnota reprezentovaná aktuálním objektem větší než hodnota reprezentovaná zadaným objektem [Nullable](./) aplikací [operator>()](./operator_greater/) na tyto hodnoty. |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | Vždy vrací false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | Určuje, zda je hodnota reprezentovaná aktuálním objektem větší nebo rovna hodnotě reprezentované zadaným objektem aplikací [operator>=()](./operator_greater_equal/) na tyto hodnoty. |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | Určuje, zda je hodnota reprezentovaná aktuálním objektem větší nebo rovna hodnotě reprezentované zadaným objektem [Nullable](./) aplikací [operator>=()](./operator_greater_equal/) na tyto hodnoty. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | Aplikuje [operator|=()](./operator_or_equal/) na hodnotu reprezentovanou aktuálním objektem s použitím zadané hodnoty jako pravého argumentu. |
| void [reset](./reset/)() | Nastavuje aktuálně reprezentovanou hodnotu na null. |
| void [set_Value](./set_value/)(const T\&) | Nastavuje novou hodnotu nullable objektu. |
| [String](../string/) [ToString](./tostring/)() const | Převádí hodnotu reprezentovanou aktuálním objektem na řetězec. |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [ValueType](./valuetype/) | Alias pro typ hodnoty reprezentované touto třídou. |

## Poznámky

Představuje hodnotu specifikovaného typu, která může být přiřazena null. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](../smartptr/) k řízení objektů tohoto typu.

## Viz také

* Namespace [System](../)
* Knihovna [Aspose.Slides](../../)