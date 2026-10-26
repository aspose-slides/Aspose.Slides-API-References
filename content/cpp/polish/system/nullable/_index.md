---
title: Nullable
second_title: Referencja API Aspose.Slides dla C++
description: Deklaracja wstępna.
type: docs
weight: 1106
url: /pl/system/nullable/
---
## Klasa Nullable


Deklaracja wstępna.

```cpp
template<typename T>class Nullable
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ wartości bazowej, który jest rozszerzany przez klasę [Nullable](./) |
## Metody

| Metoda | Opis |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | Określa, czy wartość reprezentowana przez bieżący obiekt jest równa wartości reprezentowanej przez określony obiekt [Nullable](./). |
| **bool** [get_HasValue](./get_hasvalue/)() const | Określa, czy bieżący obiekt reprezentuje jakąkolwiek wartość. |
| T [get_Value](./get_value/)() const | Zwraca kopię wartości reprezentowanej przez bieżący obiekt. |
| int [GetHashCode](./gethashcode/)() const | Zwraca kod skrótu (hash) dla bieżącego obiektu. |
| T [GetValueOrDefault](./getvalueordefault/)(T) | Zwraca wartość reprezentowaną przez bieżący obiekt lub podaną wartość, jeśli wartość reprezentowana przez bieżący obiekt jest nullem. |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | Określa, czy bieżący obiekt reprezentuje wartość null. |
|  [Nullable](./nullable/)() | Tworzy instancję reprezentującą wartość null. |
|  [Nullable](./nullable/)(std::nullptr_t) | Tworzy instancję reprezentującą null. |
|  [Nullable](./nullable/)(const T1\&) | Tworzy instancję klasy [Nullable](./), która reprezentuje podaną wartość przekonwertowaną (w razie potrzeby) na typ podstawowy T. |
|  [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | Tworzy instancję, która reprezentuje wartość reprezentowaną przez określony obiekt [Nullable](./). Określony obiekt nullable może reprezentować wartość innego typu niż typ podstawowy tworzonej instancji; w takim przypadku reprezentowana wartość jest konwertowana na typ T. |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | Funkcja pomocnicza sprawdzająca, czy zarówno bieżący, jak i **inny** nie są nullem i wywołująca lambda, jeśli tak jest. Używana w implementacjach. |
|  [operator const T &](./operator_const_t__and/)() const | Zwraca stałe odwołanie do wartości reprezentowanej przez bieżący obiekt. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Określa, czy wartość reprezentowana przez bieżący obiekt nie jest nullem. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | Określa, czy wartość reprezentowana przez bieżący obiekt nie jest równa podanej wartości. |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | Określa, czy wartość reprezentowana przez bieżący obiekt nie jest równa wartości reprezentowanej przez określony obiekt [Nullable](./). |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | Zastosowuje [operator&=()](./operator_and_equal/) do wartości reprezentowanej przez bieżący obiekt, używając podanej wartości jako argumentu po prawej stronie. |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | Zwraca domyślnie skonstruowaną instancję klasy Nullable<T>. |
| auto [operator+](./operator_plus/)(const T1\&) const | Sumuje wartości nullable i nie-nullable. |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | Sumuje wartości nullable. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | Resetuje bieżący obiekt, aby reprezentował wartość null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | Zastosowuje [operator+=()](./operator_plus_equal/) do wartości reprezentowanej przez bieżący obiekt, używając podanej wartości jako argumentu po prawej stronie. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | Zastosowuje [operator+=()](./operator_plus_equal/) do wartości reprezentowanej przez bieżący obiekt, używając wartości reprezentowanej przez określony obiekt [Nullable](./) jako argumentu po prawej stronie. |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | Odejmuje wartości nullable i wskaźniki na null. |
| auto [operator-](./operator_minus/)(const T1\&) const | Odejmuje wartości nullable i nie-nullable. |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | Odejmuje wartości nullable. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | Zwraca instancję klasy [Nullable](./), która reprezentuje wartość null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | Zastosowuje [operator-=()](./operator_minus_equal/) do wartości reprezentowanej przez bieżący obiekt, używając podanej wartości jako argumentu po prawej stronie. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | Zastosowuje [operator-=()](./operator_minus_equal/) do wartości reprezentowanej przez bieżący obiekt, używając wartości reprezentowanej przez określony obiekt [Nullable](./) jako argumentu po prawej stronie. |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | Zawsze zwraca false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | Określa, czy wartość reprezentowana przez bieżący obiekt jest mniejsza od podanej wartości, stosując [operator<()](./operator_less/) do tych wartości. |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | Określa, czy wartość reprezentowana przez bieżący obiekt jest mniejsza od wartości reprezentowanej przez określony obiekt [Nullable](./), stosując [operator<()](./operator_less/) do tych wartości. |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | Zawsze zwraca false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | Określa, czy wartość reprezentowana przez bieżący obiekt jest mniejsza lub równa podanej wartości, stosując [operator<=()](./operator_less_equal/) do tych wartości. |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | Określa, czy wartość reprezentowana przez bieżący obiekt jest mniejsza lub równa wartości reprezentowanej przez określony obiekt [Nullable](./), stosując [operator<=()](./operator_less_equal/) do tych wartości. |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | Przypisuje null do bieżącego obiektu. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | Zastępuje aktualnie reprezentowaną wartość obiektu podaną wartością. |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | Zastępuje aktualnie reprezentowaną wartość obiektu podaną wartością. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Określa, czy wartość reprezentowana przez bieżący obiekt jest null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | Określa, czy wartość reprezentowana przez bieżący obiekt jest równa podanej wartości. |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | Określa, czy wartość reprezentowana przez bieżący obiekt jest równa wartości reprezentowanej przez określony obiekt [Nullable](./). |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | Zawsze zwraca false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | Określa, czy wartość reprezentowana przez bieżący obiekt jest większa od podanej wartości, stosując [operator>()](./operator_greater/) do tych wartości. |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | Określa, czy wartość reprezentowana przez bieżący obiekt jest większa od wartości reprezentowanej przez określony obiekt [Nullable](./), stosując [operator>()](./operator_greater/) do tych wartości. |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | Zawsze zwraca false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | Określa, czy wartość reprezentowana przez bieżący obiekt jest większa lub równa wartości reprezentowanej przez podany obiekt, stosując [operator>=()](./operator_greater_equal/) do tych wartości. |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | Określa, czy wartość reprezentowana przez bieżący obiekt jest większa lub równa wartości reprezentowanej przez określony obiekt [Nullable](./), stosując [operator>=()](./operator_greater_equal/) do tych wartości. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | Zastosowuje [operator|=()](./operator_or_equal/) do wartości reprezentowanej przez bieżący obiekt, używając podanej wartości jako argumentu po prawej stronie. |
| void [reset](./reset/)() | Ustawia aktualnie reprezentowaną wartość na null. |
| void [set_Value](./set_value/)(const T\&) | Ustawia nową wartość w obiekcie nullable. |
| [String](../string/) [ToString](./tostring/)() const | Konwertuje wartość reprezentowaną przez bieżący obiekt na łańcuch znaków. |
## Typedefy

| Typedef | Opis |
| --- | --- |
| [ValueType](./valuetype/) | Alias dla typu wartości reprezentowanej przez tę klasę. |
## Uwagi


Reprezentuje wartość określonego typu, którą można przypisać jako null. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy [System::SmartPtr](../smartptr/) do zarządzania obiektami tego typu.

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)