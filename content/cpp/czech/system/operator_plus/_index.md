---
title: operator+()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací novou instanci třídy Decimal, která představuje hodnotu, jež je součtem zadané hodnoty a hodnoty reprezentované zadaným objektem Decimal.
type: docs
weight: 2185
url: /cs/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) funkce


Vrací novou instanci třídy [Decimal](../decimal/), která představuje hodnotu, jež je součtem zadané hodnoty a hodnoty reprezentované zadaným objektem [Decimal](../decimal/).

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```


### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | const T\& | První sčítanec |
| d | const [Decimal](../decimal/)\& | Konstantní reference na objekt [Decimal](../decimal/) představující druhý sčítanec |

### Návratová hodnota

Nová instance třídy [Decimal](../decimal/), která představuje hodnotu, jež je součtem **x** a hodnoty reprezentované **d**.

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) funkce


Připojí všechny zpětné volání z delegáta pravé ruky na konec seznamu zpětných volání delegáta levé ruky.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Delegát, ke kterému jsou přidávána zpětná volání. |
| rhv | MulticastDelegate\<T\> | Delegát, jehož zpětná volání jsou přidávána. |

### Návratová hodnota

Vrací delegát, který obsahuje zpětná volání levé hodnoty a poté pravé.

## System::operator+(const T1\&, const Nullable\<T2\>\&) funkce


Sečte nenullovatelné a nullovatelné hodnoty.

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```


### Template parameters

| Parametr | Popis |
| --- | --- |
| T1 | Typ levého operandu. |
| T2 | Typ pravého operandu. |

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| some | const T1\& | Levý operand. |
| other | const [Nullable](../nullable/)\<T2\>\& | Pravý operand. |

### Návratová hodnota

Výsledek sčítání.

## System::operator+(T\&, const String\&) funkce


[String](../string/) konkatenace.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


### Template parameters

| Parametr | Popis |
| --- | --- |
| T | [String](../string/) typ literálu. |

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| left | T\& | Literál k připojení ke stringu. |
| right | const [String](../string/)\& | [String](../string/) k připojení. |

### Návratová hodnota

Spojený řetězec.

## System::operator+(T\&, const String\&) funkce


[String](../string/) konkatenace.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


### Template parameters

| Parametr | Popis |
| --- | --- |
| T | [String](../string/) typ ukazatele. |

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| left | T\& | [String](../string/) ukazatel k připojení ke stringu. |
| right | const [String](../string/)\& | [String](../string/) k připojení. |

### Návratová hodnota

Spojený řetězec.

## System::operator+(const char_t, const String\&) funkce


[String](../string/) konkatenace.

```cpp
String System::operator+(const char_t left, const String &right)
```


### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| left | const char_t | Znak k připojení ke stringu. |
| right | const [String](../string/)\& | [String](../string/) k připojení. |

### Návratová hodnota

Spojený řetězec.

## Viz také

* Třída [Decimal](../decimal/)
* Třída [Nullable](../nullable/)
* Třída [String](../string/)
* Struktura [IsStringLiteral](../isstringliteral/)
* Struktura [IsStringPointer](../isstringpointer/)
* Namespace [System](../)
* Knihovna [Aspose.Slides](../../)