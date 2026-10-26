---
title: operator+()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt eine neue Instanz der Klasse Decimal zurück, die einen Wert darstellt, der die Summe des angegebenen Wertes und des durch das angegebene Decimal-Objekt dargestellten Wertes ist.
type: docs
weight: 2185
url: /de/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) Funktion


Gibt eine neue Instanz der Klasse [Decimal](../decimal/) zurück, die einen Wert darstellt, der die Summe des angegebenen Wertes und des durch das angegebene [Decimal](../decimal/)-Objekt dargestellten Wertes ist.

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | const T\& | Der erste Summand |
| d | const [Decimal](../decimal/)\& | Die konstante Referenz auf das [Decimal](../decimal/)-Objekt, das den zweiten Summanden darstellt |

### Rückgabewert

Eine neue Instanz der Klasse [Decimal](../decimal/), die einen Wert darstellt, der die Summe von **x** und dem durch **d** dargestellten Wert ist.

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) Funktion


Verbindet alle Rückruffunktionen des rechten Delegaten am Ende der Rückruffunktionsliste des linken Delegaten.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Der Delegat, zu dem Rückruffunktionen hinzugefügt werden. |
| rhv | MulticastDelegate\<T\> | Der Delegat, dessen Rückruffunktionen hinzugefügt werden. |

### Rückgabewert

Gibt einen Delegaten zurück, der die Rückruffunktionen des linken Werts und anschließend die des rechten enthält.

## System::operator+(const T1\&, const Nullable\<T2\>\&) Funktion


Addiert nicht-nullbare und nullable Werte.

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Typ des linken Operanden. |
| T2 | Typ des rechten Operanden. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| some | const T1\& | Linker Operand. |
| other | const [Nullable](../nullable/)\<T2\>\& | Rechter Operand. |

### Rückgabewert

Summierergebnis.

## System::operator+(T\&, const String\&) Funktion


[String](../string/) Verkettung.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [String](../string/) Literaltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | T\& | Literal zum Anhängen an Zeichenkette. |
| right | const [String](../string/)\& | [String](../string/) zum Verketten. |

### Rückgabewert

Verkettete Zeichenkette.

## System::operator+(T\&, const String\&) Funktion


[String](../string/) Verkettung.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [String](../string/) Zeigertyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | T\& | [String](../string/) Zeiger zum Anhängen an Zeichenkette. |
| right | const [String](../string/)\& | [String](../string/) zum Verketten. |

### Rückgabewert

Verkettete Zeichenkette.

## System::operator+(const char_t, const String\&) Funktion


[String](../string/) Verkettung.

```cpp
String System::operator+(const char_t left, const String &right)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | const char_t | Zeichen, das an Zeichenkette angehängt wird. |
| right | const [String](../string/)\& | [String](../string/) zum Verketten. |

### Rückgabewert

Verkettete Zeichenkette.

## Siehe auch

* Klasse [Decimal](../decimal/)
* Klasse [Nullable](../nullable/)
* Klasse [String](../string/)
* Struktur [IsStringLiteral](../isstringliteral/)
* Struktur [IsStringPointer](../isstringpointer/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)