---
title: operator+()
second_title: Aspose.Slides voor C++ API-referentie
description: String-concatenatie-operator.
type: docs
weight: 274
url: /nl/system/string/operator_plus/
---
## String::operator+(const String\&) const methode


[String](../) concatenatie-operator.

```cpp
String System::String::operator+(const String &str) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) om toe te voegen aan het einde van de huidige. |

### Retourwaarde

Samengevoegde string.

## String::operator+(const T\&) const methode


[String](../) concatenatie met stringliteral of tekenreeks-pointer.

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Een van de vormen van stringliteral of tekenreeks-pointer. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg | const T\& | Entiteit om samen te voegen met de huidige string. |

### Retourwaarde

Samengevoegde string.

## String::operator+(char_t) const methode


Voegt een teken toe aan het einde van de string.

```cpp
String System::String::operator+(char_t x) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | char_t | Teken om toe te voegen. |

### Retourwaarde

[String](../) concatenatieresultaat.

## String::operator+(int) const methode


Voegt de tekenreeksrepresentatie van een geheel getal toe aan het einde van de string.

```cpp
String System::String::operator+(int i) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| i | int | Gehele getalwaarde om te converteren naar string en toe te voegen. |

### Retourwaarde

[String](../) concatenatieresultaat.

## String::operator+(uint32_t) const methode


Voegt de tekenreeksrepresentatie van een ongeondertekend geheel getal toe aan het einde van de string.

```cpp
String System::String::operator+(uint32_t i) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| i | **uint32_t** | Waarde om te converteren naar string en toe te voegen. |

### Retourwaarde

[String](../) concatenatieresultaat.

## String::operator+(double) const methode


Voegt de tekenreeksrepresentatie van een zwevend-kommagetal toe aan het einde van de string.

```cpp
String System::String::operator+(double d) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| d | **double** | Waarde om te converteren naar string en toe te voegen. |

### Retourwaarde

[String](../) concatenatieresultaat.

## String::operator+(int64_t) const methode


Voegt de tekenreeksrepresentatie van een geheel getal toe aan het einde van de string.

```cpp
String System::String::operator+(int64_t v) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| v | **int64_t** | Waarde om te converteren naar string en toe te voegen. |

### Retourwaarde

[String](../) concatenatieresultaat.

## String::operator+(const T\&) const methode


Voegt de tekenreeksrepresentatie van een referentie-type-object toe aan het einde van de string.

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | pointertype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) om te converteren naar string met behulp van [ToString()](../tostring/)-oproep en toe te voegen aan de huidige string. |

### Retourwaarde

[String](../) concatenatieresultaat.

## String::operator+(const T\&) const methode


Voegt de tekenreeksrepresentatie van een waardetype-object toe aan het einde van de string.

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Waardetype om [ToString()](../tostring/) op aan te roepen. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) om te converteren naar string met behulp van [ToString()](../tostring/)-oproep en toe te voegen aan de huidige string. |

### Retourwaarde

[String](../) concatenatieresultaat.

## String::operator+(T) const methode


Voegt de tekenreeksrepresentatie van een booleaanse waarde toe aan het einde van de string.

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Waardetype om samen te voegen met string. Moet bool zijn |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) waarde om te converteren naar string en toe te voegen. |

### Retourwaarde

[String](../) concatenatieresultaat.

## Zie ook

* Klasse [String](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)