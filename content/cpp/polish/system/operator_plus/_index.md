---
title: operator+()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Zwraca nową instancję klasy Decimal, która reprezentuje wartość będącą sumą podanej wartości oraz wartości reprezentowanej przez określony obiekt Decimal.
type: docs
weight: 2185
url: /pl/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) funkcja

Zwraca nową instancję klasy [Decimal](../decimal/), która reprezentuje wartość będącą sumą podanej wartości oraz wartości reprezentowanej przez określony obiekt [Decimal](../decimal/).

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | const T\& | Pierwszy składnik |
| d | const [Decimal](../decimal/)\& | Stałe odwołanie do obiektu [Decimal](../decimal/) reprezentującego drugi składnik |

### Wartość zwracana

Nowa instancja klasy [Decimal](../decimal/), która reprezentuje wartość będącą sumą **x** oraz wartości reprezentowanej przez **d**.

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) funkcja

Łączy wszystkie wywołania zwrotne z delegata po prawej stronie z końcem listy wywołań zwrotnych delegata po lewej stronie.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Delegat, do którego są dodawane wywołania zwrotne. |
| rhv | MulticastDelegate\<T\> | Delegat, którego wywołania zwrotne są dodawane. |

### Wartość zwracana

Zwraca delegata, który zawiera wywołania zwrotne wartości po lewej stronie, a następnie wywołania po prawej stronie.

## System::operator+(const T1\&, const Nullable\<T2\>\&) funkcja

Sumuje wartości nie-nulowalne i nulowalne.

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ lewego operandu. |
| T2 | Typ prawego operandu. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| some | const T1\& | Lewy operand. |
| other | const [Nullable](../nullable/)\<T2\>\& | Prawy operand. |

### Wartość zwracana

Wynik sumowania.

## System::operator+(T\&, const String\&) funkcja

[String](../string/) konkatenacja.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | [String](../string/) typ literału. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| left | T\& | Literał do konkatenacji z ciągiem. |
| right | const [String](../string/)\& | [String](../string/) do konkatenacji. |

### Wartość zwracana

Połączony ciąg.

## System::operator+(T\&, const String\&) funkcja

[String](../string/) konkatenacja.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | [String](../string/) typ wskaźnika. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| left | T\& | [String](../string/) wskaźnik do konkatenacji z ciągiem. |
| right | const [String](../string/)\& | [String](../string/) do konkatenacji. |

### Wartość zwracana

Połączony ciąg.

## System::operator+(const char_t, const String\&) funkcja

[String](../string/) konkatenacja.

```cpp
String System::operator+(const char_t left, const String &right)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| left | const char_t | Znak do konkatenacji z ciągiem. |
| right | const [String](../string/)\& | [String](../string/) do konkatenacji. |

### Wartość zwracana

Połączony ciąg.

## Zobacz także

* Klasa [Decimal](../decimal/)
* Klasa [Nullable](../nullable/)
* Klasa [String](../string/)
* Struktura [IsStringLiteral](../isstringliteral/)
* Struktura [IsStringPointer](../isstringpointer/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)