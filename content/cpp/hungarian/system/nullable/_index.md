---
title: Nullable
second_title: Aspose.Slides C++ API Referencia
description: Előzetes deklaráció.
type: docs
weight: 1106
url: /hu/system/nullable/
---
## Nullable osztály

Forward declaration.

```cpp
template<typename T>class Nullable
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az alapérték típus, amelyet a [Nullable](./) osztály kibővít. |

## Módszerek

| Módszer | Leírás |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | Meghatározza, hogy a jelenlegi objektum által képviselt érték egyenlő-e a megadott [Nullable](./) objektum által képviselt értékkel. |
| **bool** [get_HasValue](./get_hasvalue/)() const | Meghatározza, hogy a jelenlegi objektum képvisel-e bármilyen értéket. |
| T [get_Value](./get_value/)() const | Visszaadja a jelenlegi objektum által képviselt érték másolatát. |
| int [GetHashCode](./gethashcode/)() const | Visszaad egy hash-kódot a jelenlegi objektumhoz. |
| T [GetValueOrDefault](./getvalueordefault/)(T) | Visszaadja a jelenlegi objektum által képviselt értéket, vagy a megadott értéket, ha a jelenlegi objektum által képviselt érték null. |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | Meghatározza, hogy a jelenlegi objektum null-értéket képvisel-e. |
| [Nullable](./nullable/)() | Létrehoz egy példányt, amely null-értéket képvisel. |
| [Nullable](./nullable/)(std::nullptr_t) | Létrehoz egy példányt, amely null értéket képvisel. |
| [Nullable](./nullable/)(const T1\&) | Létrehoz egy [Nullable](./) osztály példányt, amely a megadott értéket (szükség esetén) az alap típusú T értékké konvertálva képviseli. |
| [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | Létrehoz egy példányt, amely a megadott [Nullable](./) objektum által képviselt értéket reprezentálja. A megadott nullable objektum eltérő típusú értéket képviselhet, mint a létrehozott példány alap típusa, ebben az esetben a képviselt érték T típusra konvertálódik. |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | Segédfüggvény annak ellenőrzésére, hogy ez és **other** is nem null, és ha igen, meghív egy lambda kifejezést. Implementációkban használják. |
| [operator const T &](./operator_const_t__and/)() const | Visszaad egy konstans referenciát a jelenlegi objektum által képviselt értékhez. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Meghatározza, hogy a jelenlegi objektum által képviselt érték nem null-e. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | Meghatározza, hogy a jelenlegi objektum által képviselt érték nem egyenlő-e a megadott értékkel. |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | Meghatározza, hogy a jelenlegi objektum által képviselt érték nem egyenlő-e a megadott [Nullable](./) objektum által képviselt értékkel. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | [operator&=()](./operator_and_equal/) alkalmazza a jelenlegi objektum által képviselt értékre a megadott értéket jobb oldali argumentumként. |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | Visszaad egy alapértelmezett konstrukcióval létrehozott Nullable<T> osztály példányt. |
| auto [operator+](./operator_plus/)(const T1\&) const | Összeadja a nullable és a nem nullable értékeket. |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | Összeadja a nullable értékeket. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | Visszaállítja a jelenlegi objektumot, hogy null-értéket képviseljen. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | [operator+=()](./operator_plus_equal/) alkalmazza a jelenlegi objektum által képviselt értékre a megadott értéket jobb oldali argumentumként. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | [operator+=()](./operator_plus_equal/) alkalmazza a jelenlegi objektum által képviselt értékre a megadott [Nullable](./) objektum által képviselt értéket jobb oldali argumentumként. |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | Kivonja a nullable és null mutató értékeket. |
| auto [operator-](./operator_minus/)(const T1\&) const | Kivonja a nullable és a nem nullable értékeket. |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | Kivonja a nullable értékeket. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | Visszaad egy [Nullable](./) osztály példányt, amely null-értéket képvisel. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | [operator-=()](./operator_minus_equal/) alkalmazza a jelenlegi objektum által képviselt értékre a megadott értéket jobb oldali argumentumként. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | [operator-=()](./operator_minus_equal/) alkalmazza a jelenlegi objektum által képviselt értékre a megadott [Nullable](./) objektum által képviselt értéket jobb oldali argumentumként. |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | Mindig hamisat ad vissza. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | Meghatározza, hogy a jelenlegi objektum által képviselt érték kisebb-e a megadott értéknél, a [operator<()](./operator_less/) alkalmazásával. |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | Meghatározza, hogy a jelenlegi objektum által képviselt érték kisebb-e a megadott [Nullable](./) objektum által képviselt értéknél, a [operator<()](./operator_less/) alkalmazásával. |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | Mindig hamisat ad vissza. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | Meghatározza, hogy a jelenlegi objektum által képviselt érték kisebb vagy egyenlő-e a megadott értékkel, a [operator<=()](./operator_less_equal/) alkalmazásával. |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | Meghatározza, hogy a jelenlegi objektum által képviselt érték kisebb vagy egyenlő-e a megadott [Nullable](./) objektum által képviselt értékkel, a [operator<=()](./operator_less_equal/) alkalmazásával. |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | Null értéket rendel a jelenlegi objektumhoz. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | A megadott értékkel felülírja az objektum jelenleg képviselt értékét. |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | A megadott értékkel felülírja az objektum jelenleg képviselt értékét. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Meghatározza, hogy a jelenlegi objektum által képviselt érték null-e. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | Meghatározza, hogy a jelenlegi objektum által képviselt érték egyenlő-e a megadott értékkel. |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | Meghatározza, hogy a jelenlegi objektum által képviselt érték egyenlő-e a megadott [Nullable](./) objektum által képviselt értékkel. |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | Mindig hamisat ad vissza. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | Meghatározza, hogy a jelenlegi objektum által képviselt érték nagyobb-e a megadott értéknél, a [operator>()](./operator_greater/) alkalmazásával. |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | Meghatározza, hogy a jelenlegi objektum által képviselt érték nagyobb-e a megadott [Nullable](./) objektum által képviselt értéknél, a [operator>()](./operator_greater/) alkalmazásával. |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | Mindig hamisat ad vissza. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | Meghatározza, hogy a jelenlegi objektum által képviselt érték nagyobb vagy egyenlő-e a megadott objektum értékével, a [operator>=()](./operator_greater_equal/) alkalmazásával. |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | Meghatározza, hogy a jelenlegi objektum által képviselt érték nagyobb vagy egyenlő-e a megadott [Nullable](./) objektum által képviselt értékkel, a [operator>=()](./operator_greater_equal/) alkalmazásával. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | [operator|=()](./operator_or_equal/) alkalmazza a jelenlegi objektum által képviselt értékre a megadott értéket jobb oldali argumentumként. |
| void [reset](./reset/)() | A jelenleg képviselt értéket null-ra állítja. |
| void [set_Value](./set_value/)(const T\&) | Új értéket állít be a nullable objektumnak. |
| [String](../string/) [ToString](./tostring/)() const | A jelenlegi objektum által képviselt értéket stringgé konvertálja. |
## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [ValueType](./valuetype/) | Egy alias a jelen osztály által képviselt érték típusához. |
## Megjegyzések

Egy olyan értéket képvisel a megadott típusban, amelyhez null érték rendelhető. Ezt a típust a stacken kell példányosítani, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../smartptr/) osztályt ennek a típusnak az objektumainak kezelésére.

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)