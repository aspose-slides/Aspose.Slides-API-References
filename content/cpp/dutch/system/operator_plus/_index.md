---
title: operator+()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een nieuw exemplaar van de Decimal-klasse die een waarde vertegenwoordigt die de som is van de opgegeven waarde en de waarde die wordt vertegenwoordigd door het opgegeven Decimal-object.
type: docs
weight: 2185
url: /nl/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) functie

Retourneert een nieuw exemplaar van de [Decimal](../decimal/) klasse die een waarde vertegenwoordigt die de som is van de opgegeven waarde en de waarde die wordt vertegenwoordigd door het opgegeven [Decimal](../decimal/) object.

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | const T\& | De eerste term |
| d | const [Decimal](../decimal/)\& | De constante referentie naar het [Decimal](../decimal/) object dat de tweede term vertegenwoordigt |

### Retourwaarde

Een nieuw exemplaar van de [Decimal](../decimal/) klasse die een waarde vertegenwoordigt die de som is van **x** en de waarde die wordt vertegenwoordigd door **d**.

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) functie

Verbindt alle callbacks van de rechterdelegate met het einde van de callback-lijst van de linkerdelegate.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | De delegate waaraan callbacks worden toegevoegd. |
| rhv | MulticastDelegate\<T\> | De delegate waarvan de callbacks worden toegevoegd. |

### Retourwaarde

Retourneert een delegate die de callbacks van de linkerkant bevat en daarna die van de rechterkant.

## System::operator+(const T1\&, const Nullable\<T2\>\&) functie

Somt niet-nullbare en nullbare waarden op.

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Type van de linkeroperand. |
| T2 | Type van de rechteroperand. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| some | const T1\& | Linkeroperand. |
| other | const [Nullable](../nullable/)\<T2\>\& | Rechteroperand. |

### Retourwaarde

Somresultaat.

## System::operator+(T\&, const String\&) functie

[String](../string/) concatenatie.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [String](../string/) lettertype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | T\& | Letterlijk om aan de string te concatenaten. |
| right | const [String](../string/)\& | [String](../string/) om te concatenaten. |

### Retourwaarde

Samengevoegde string.

## System::operator+(T\&, const String\&) functie

[String](../string/) concatenatie.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [String](../string/) pointertype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | T\& | [String](../string/) pointer om aan de string te concatenaten. |
| right | const [String](../string/)\& | [String](../string/) om te concatenaten. |

### Retourwaarde

Samengevoegde string.

## System::operator+(const char_t, const String\&) functie

[String](../string/) concatenatie.

```cpp
String System::operator+(const char_t left, const String &right)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | const char_t | Teken om aan de string te concatenaten. |
| right | const [String](../string/)\& | [String](../string/) om te concatenaten. |

### Retourwaarde

Samengevoegde string.

## Zie ook

* Klasse [Decimal](../decimal/)
* Klasse [Nullable](../nullable/)
* Klasse [String](../string/)
* Struct [IsStringLiteral](../isstringliteral/)
* Struct [IsStringPointer](../isstringpointer/)
* Naamruimte [System](../)
* Library [Aspose.Slides](../../)