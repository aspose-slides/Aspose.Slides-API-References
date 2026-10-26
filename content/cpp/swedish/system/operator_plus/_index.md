---
title: operator+()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en ny instans av Decimal-klassen som representerar ett värde som är summan av det angivna värdet och värdet som representeras av det angivna Decimal-objektet.
type: docs
weight: 2185
url: /sv/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) funktion

Returnerar en ny instans av [Decimal](../decimal/) klass som representerar ett värde som är summan av det angivna värdet och värdet som representeras av det angivna [Decimal](../decimal/)-objektet.

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const T\& | Den första summanden |
| d | const [Decimal](../decimal/)\& | Den konstanta referensen till [Decimal](../decimal/)-objektet som representerar den andra summanden |

### Returvärde

En ny instans av [Decimal](../decimal/) klass som representerar ett värde som är summan av **x** och värdet som representeras av **d**.

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) funktion

Kopplar alla återanrop från högra delegaten till slutet av vänstra delegatens återanropslista.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Delegaten som återanrop läggs till. |
| rhv | MulticastDelegate\<T\> | Delegaten vars återanrop läggs till. |

### Returvärde

Returnerar en delegate som innehåller återanropen från den vänstra delegaten och sedan de från den högra delegaten.

## System::operator+(const T1\&, const Nullable\<T2\>\&) funktion

Adderar icke-nollbara och nullable-värden.

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Typ av vänster operand. |
| T2 | Typ av höger operand. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| some | const T1\& | Vänster operand. |
| other | const [Nullable](../nullable/)\<T2\>\& | Höger operand. |

### Returvärde

Resultat av summeringen.

## System::operator+(T\&, const String\&) funktion

[String](../string/) konkatenering.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [String](../string/) literaltyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | T\& | Literal att konkatenera till sträng. |
| right | const [String](../string/)\& | [String](../string/) att konkatenera. |

### Returvärde

Konkatenerad sträng.

## System::operator+(T\&, const String\&) funktion

[String](../string/) konkatenering.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [String](../string/) pekartyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | T\& | [String](../string/) pekare att konkatenera till sträng. |
| right | const [String](../string/)\& | [String](../string/) att konkatenera. |

### Returvärde

Konkatenerad sträng.

## System::operator+(const char_t, const String\&) funktion

[String](../string/) konkatenering.

```cpp
String System::operator+(const char_t left, const String &right)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | const char_t | Tecken att konkatenera till sträng. |
| right | const [String](../string/)\& | [String](../string/) att konkatenera. |

### Returvärde

Konkatenerad sträng.

## Se även

* Klass [Decimal](../decimal/)
* Klass [Nullable](../nullable/)
* Klass [String](../string/)
* Struktur [IsStringLiteral](../isstringliteral/)
* Struktur [IsStringPointer](../isstringpointer/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)