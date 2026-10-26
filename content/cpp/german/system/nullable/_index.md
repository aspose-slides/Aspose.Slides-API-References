---
title: Nullable
second_title: Aspose.Slides für C++ API-Referenz
description: Vorwärtsdeklaration.
type: docs
weight: 1106
url: /de/system/nullable/
---
## Nullable Klasse

Forward declaration.

```cpp
template<typename T>class Nullable
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der zugrunde liegende Werttyp, der von der [Nullable](./) Klasse erweitert wird. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert dem vom angegebenen [Nullable](./) Objekt dargestellten Wert entspricht. |
| **bool** [get_HasValue](./get_hasvalue/)() const | Bestimmt, ob das aktuelle Objekt irgendeinen Wert darstellt. |
| T [get_Value](./get_value/)() const | Gibt eine Kopie des vom aktuellen Objekt dargestellten Werts zurück. |
| int [GetHashCode](./gethashcode/)() const | Gibt einen Hashcode für das aktuelle Objekt zurück. |
| T [GetValueOrDefault](./getvalueordefault/)(T) | Gibt den vom aktuellen Objekt dargestellten Wert zurück oder den angegebenen Wert, falls der vom aktuellen Objekt dargestellte Wert null ist. |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | Bestimmt, ob das aktuelle Objekt einen Nullwert darstellt. |
|  [Nullable](./nullable/)() | Konstruiert eine Instanz, die einen Nullwert darstellt. |
|  [Nullable](./nullable/)(std::nullptr_t) | Konstruiert eine Instanz, die null darstellt. |
|  [Nullable](./nullable/)(const T1\&) | Konstruiert eine Instanz der [Nullable](./) Klasse, die den angegebenen Wert darstellt, der (falls erforderlich) in den zugrunde liegenden Typ T konvertiert wird. |
|  [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | Konstruiert eine Instanz, die einen Wert darstellt, der vom angegebenen [Nullable](./) Objekt repräsentiert wird. Das angegebene nullable-Objekt kann einen Wert eines anderen Typs als den zugrunde liegenden Typ der konstruierten Instanz darstellen; in diesem Fall wird der dargestellte Wert in einen Wert vom Typ T konvertiert. |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | Hilfsfunktion, um zu prüfen, ob sowohl dieses als auch **other** nicht null sind und in diesem Fall eine Lambda-Funktion aufzurufen. Wird in Implementierungen verwendet. |
|  [operator const T &](./operator_const_t__and/)() const | Gibt eine konstante Referenz auf den vom aktuellen Objekt dargestellten Wert zurück. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert nicht null ist. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert nicht gleich dem angegebenen Wert ist. |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert nicht gleich dem vom angegebenen [Nullable](./) Objekt dargestellten Wert ist. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | Wendet [operator&=()](./operator_and_equal/) auf den vom aktuellen Objekt dargestellten Wert an, wobei der angegebene Wert als Rechtsargument verwendet wird. |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | Gibt eine standardmäßig konstruierte Instanz der Nullable<T> Klasse zurück. |
| auto [operator+](./operator_plus/)(const T1\&) const | Addiert nullable und nicht-nullable Werte. |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | Addiert nullable Werte. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | Setzt das aktuelle Objekt zurück, sodass es einen Nullwert darstellt. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | Wendet [operator+=()](./operator_plus_equal/) auf den vom aktuellen Objekt dargestellten Wert an, wobei der angegebene Wert als Rechtsargument verwendet wird. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | Wendet [operator+=()](./operator_plus_equal/) auf den vom aktuellen Objekt dargestellten Wert an, wobei der vom angegebenen [Nullable](./) Objekt dargestellte Wert als Rechtsargument verwendet wird. |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | Subtrahiert nullable und null-gezeigte Werte. |
| auto [operator-](./operator_minus/)(const T1\&) const | Subtrahiert nullable und nicht-nullable Werte. |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | Subtrahiert nullable Werte. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | Gibt eine Instanz der [Nullable](./) Klasse zurück, die einen Nullwert darstellt. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | Wendet [operator-=()](./operator_minus_equal/) auf den vom aktuellen Objekt dargestellten Wert an, wobei der angegebene Wert als Rechtsargument verwendet wird. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | Wendet [operator-=()](./operator_minus_equal/) auf den vom aktuellen Objekt dargestellten Wert an, wobei der vom angegebenen [Nullable](./) Objekt dargestellte Wert als Rechtsargument verwendet wird. |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | Gibt immer false zurück. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert kleiner ist als der angegebene Wert, indem [operator<()](./operator_less/) auf diese Werte angewendet wird. |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert kleiner ist als der vom angegebenen [Nullable](./) Objekt dargestellte Wert, indem [operator<()](./operator_less/) auf diese Werte angewendet wird. |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | Gibt immer false zurück. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert kleiner oder gleich dem angegebenen Wert ist, indem [operator<=()](./operator_less_equal/) auf diese Werte angewendet wird. |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert kleiner oder gleich dem vom angegebenen [Nullable](./) Objekt dargestellten Wert ist, indem [operator<=()](./operator_less_equal/) auf diese Werte angewendet wird. |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | Weist dem aktuellen Objekt null zu. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | Ersetzt den derzeit vom Objekt dargestellten Wert durch den angegebenen. |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | Ersetzt den derzeit vom Objekt dargestellten Wert durch den angegebenen. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert null ist. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert dem angegebenen Wert entspricht. |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert dem vom angegebenen [Nullable](./) Objekt dargestellten Wert entspricht. |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | Gibt immer false zurück. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert größer ist als der angegebene Wert, indem [operator>()](./operator_greater/) auf diese Werte angewendet wird. |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert größer ist als der vom angegebenen [Nullable](./) Objekt dargestellte Wert, indem [operator>()](./operator_greater/) auf diese Werte angewendet wird. |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | Gibt immer false zurück. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert größer oder gleich dem Wert des angegebenen Objekts ist, indem [operator>=()](./operator_greater_equal/) auf diese Werte angewendet wird. |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert größer oder gleich dem vom angegebenen [Nullable](./) Objekt dargestellten Wert ist, indem [operator>=()](./operator_greater_equal/) auf diese Werte angewendet wird. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | Wendet [operator|=()](./operator_or_equal/) auf den vom aktuellen Objekt dargestellten Wert an, wobei der angegebene Wert als Rechtsargument verwendet wird. |
| void [reset](./reset/)() | Setzt den derzeit dargestellten Wert auf null. |
| void [set_Value](./set_value/)(const T\&) | Setzt einen neuen Wert im nullable-Objekt. |
| [String](../string/) [ToString](./tostring/)() const | Konvertiert den vom aktuellen Objekt dargestellten Wert in einen String. |

## Typdefinitionen

| Typdefinition | Beschreibung |
| --- | --- |
| [ValueType](./valuetype/) | Ein Alias für einen Typ des von dieser Klasse dargestellten Werts. |

## Hinweise

Stellt einen Wert des angegebenen Typs dar, dem null zugewiesen werden kann. Dieser Typ sollte auf dem Stack allokiert und Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die [System::SmartPtr](../smartptr/) Klasse, um Objekte dieses Typs zu verwalten.

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)