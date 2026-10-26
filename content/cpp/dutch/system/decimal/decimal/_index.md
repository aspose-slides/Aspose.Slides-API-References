---
title: Decimal()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een instantie die 0 vertegenwoordigt.
type: docs
weight: 1
url: /nl/system/decimal/decimal/
---
## Decimal::Decimal() constructor

Construeert een instantie die 0 vertegenwoordigt.

```cpp
System::Decimal::Decimal()
```

## Decimal::Decimal(std::int8_t) constructor

Construeert een instantie die de opgegeven waarde vertegenwoordigt.

```cpp
System::Decimal::Decimal(std::int8_t i)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| i | std::int8_t | 8-bit geheelgetalwaarde die wordt vertegenwoordigd door het [Decimal](../)-object dat wordt geconstrueerd |

## Decimal::Decimal(std::int16_t) constructor

Construeert een instantie die de opgegeven waarde vertegenwoordigt.

```cpp
System::Decimal::Decimal(std::int16_t i)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| i | std::int16_t | 16-bit geheelgetalwaarde die wordt vertegenwoordigd door het [Decimal](../)-object dat wordt geconstrueerd |

## Decimal::Decimal(std::int32_t) constructor

Construeert een instantie die de opgegeven waarde vertegenwoordigt.

```cpp
System::Decimal::Decimal(std::int32_t i)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| i | std::int32_t | 32-bit geheelgetalwaarde die wordt vertegenwoordigd door het [Decimal](../)-object dat wordt geconstrueerd |

## Decimal::Decimal(std::int64_t) constructor

Construeert een instantie die de opgegeven waarde vertegenwoordigt.

```cpp
System::Decimal::Decimal(std::int64_t i)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| i | std::int64_t | 64-bit geheelgetalwaarde die wordt vertegenwoordigd door het [Decimal](../)-object dat wordt geconstrueerd |

## Decimal::Decimal(std::uint8_t) constructor

Construeert een instantie die de opgegeven waarde vertegenwoordigt.

```cpp
System::Decimal::Decimal(std::uint8_t i)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| i | std::uint8_t | Ongetekend 8-bit geheelgetalwaarde die wordt vertegenwoordigd door het [Decimal](../)-object dat wordt geconstrueerd |

## Decimal::Decimal(std::uint16_t) constructor

Construeert een instantie die de opgegeven waarde vertegenwoordigt.

```cpp
System::Decimal::Decimal(std::uint16_t i)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| i | std::uint16_t | Ongetekend 16-bit geheelgetalwaarde die wordt vertegenwoordigd door het [Decimal](../)-object dat wordt geconstrueerd |

## Decimal::Decimal(std::uint32_t) constructor

Construeert een instantie die de opgegeven waarde vertegenwoordigt.

```cpp
System::Decimal::Decimal(std::uint32_t i)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| i | std::uint32_t | Ongetekend 32-bit geheelgetalwaarde die wordt vertegenwoordigd door het [Decimal](../)-object dat wordt geconstrueerd |

## Decimal::Decimal(std::uint64_t) constructor

Construeert een instantie die de opgegeven waarde vertegenwoordigt.

```cpp
System::Decimal::Decimal(std::uint64_t i)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| i | std::uint64_t | Ongetekend 64-bit geheelgetalwaarde die wordt vertegenwoordigd door het [Decimal](../)-object dat wordt geconstrueerd |

## Decimal::Decimal(float) constructor

Construeert een instantie die de opgegeven waarde vertegenwoordigt.

```cpp
System::Decimal::Decimal(float f)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| f | **float** | De enkelprecisie-zwevendekommagetalwaarde die wordt vertegenwoordigd door het [Decimal](../)-object dat wordt geconstrueerd |

## Decimal::Decimal(double) constructor

Construeert een instantie die de opgegeven waarde vertegenwoordigt.

```cpp
System::Decimal::Decimal(double d)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| d | **double** | De dubbelprecisie-zwevendekommagetalwaarde die wordt vertegenwoordigd door het [Decimal](../)-object dat wordt geconstrueerd |

## Decimal::Decimal(const std::string&) constructor

Construeert een instantie die een waarde vertegenwoordigt waarvan de tekenreeksweergave is opgegeven als een instantie van de std::string-klasse.

```cpp
System::Decimal::Decimal(const std::string &str)
```

## Decimal::Decimal(int32_t, int32_t, int32_t, bool, uint8_t) constructor

Construeert een [Decimal](../)-object uit de opgegeven componenten.

```cpp
System::Decimal::Decimal(int32_t lo, int32_t mid, int32_t hi, bool isNegative, uint8_t scale)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lo | **int32_t** | De lagere 32 bits van de waarde |
| mid | **int32_t** | De middelste 32 bits van de waarde |
| hi | **int32_t** | De hogere 32 bits van de waarde |
| isNegative | **bool** | Geeft aan of de waarde negatief is |
| scale | **uint8_t** | Een macht van 10, variërend van 0 tot 28 |

## Decimal::Decimal(const Decimal&) constructor

Construeert een instantie van de [Decimal](../)-klasse die hetzelfde getal vertegenwoordigt als het opgegeven [Decimal](../)-object.

```cpp
System::Decimal::Decimal(const Decimal &d)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| d | const [Decimal](../)& | Een [Decimal](../)-object waaruit de waarde gekopieerd moet worden |

## Decimal::Decimal(const ArrayPtr<int32_t>&) constructor

Construeert een instantie van de [Decimal](../)-klasse uit een geheelgetallenarray die een binaire representatie bevat.

```cpp
System::Decimal::Decimal(const ArrayPtr<int32_t> &bits)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bits | const [ArrayPtr](../../arrayptr/)<**int32_t**>& | Een geheelgetallenarray die een binaire representatie bevat. |

## Decimal::Decimal(std::nullptr_t) constructor

Gooit altijd ArgumentNullException.

```cpp
System::Decimal::Decimal(std::nullptr_t bits)
```

## Decimal::Decimal(const number_type&) constructor

Construeert een instantie van de [Decimal](../)-klasse die de opgegeven waarde vertegenwoordigt.

```cpp
System::Decimal::Decimal(const number_type &value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [number_type](../number_type/)& | Een constante referentie naar de waarde die moet worden vertegenwoordigd door het te construeren object |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [number_type](../number_type/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)