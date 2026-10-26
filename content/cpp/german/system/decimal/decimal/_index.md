---
title: Decimal()
second_title: Aspose.Slides für C++ API Referenz
description: Konstruiert eine Instanz, die 0 darstellt.
type: docs
weight: 1
url: /de/system/decimal/decimal/
---
## Decimal::Decimal() Konstruktor

Konstruiert eine Instanz, die 0 darstellt.

```cpp
System::Decimal::Decimal()
```

## Decimal::Decimal(std::int8_t) Konstruktor

Konstruiert eine Instanz, die den angegebenen Wert darstellt.

```cpp
System::Decimal::Decimal(std::int8_t i)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| i | std::int8_t | 8-Bit-Ganzzahlwert, der vom zu erstellenden [Decimal](../)-Objekt dargestellt wird |

## Decimal::Decimal(std::int16_t) Konstruktor

Konstruiert eine Instanz, die den angegebenen Wert darstellt.

```cpp
System::Decimal::Decimal(std::int16_t i)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| i | std::int16_t | 16-Bit-Ganzzahlwert, der vom zu erstellenden [Decimal](../)-Objekt dargestellt wird |

## Decimal::Decimal(std::int32_t) Konstruktor

Konstruiert eine Instanz, die den angegebenen Wert darstellt.

```cpp
System::Decimal::Decimal(std::int32_t i)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| i | std::int32_t | 32-Bit-Ganzzahlwert, der vom zu erstellenden [Decimal](../)-Objekt dargestellt wird |

## Decimal::Decimal(std::int64_t) Konstruktor

Konstruiert eine Instanz, die den angegebenen Wert darstellt.

```cpp
System::Decimal::Decimal(std::int64_t i)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| i | std::int64_t | 64-Bit-Ganzzahlwert, der vom zu erstellenden [Decimal](../)-Objekt dargestellt wird |

## Decimal::Decimal(std::uint8_t) Konstruktor

Konstruiert eine Instanz, die den angegebenen Wert darstellt.

```cpp
System::Decimal::Decimal(std::uint8_t i)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| i | std::uint8_t | 8-Bit-vorzeichenloser Ganzzahlwert, der vom zu erstellenden [Decimal](../)-Objekt dargestellt wird |

## Decimal::Decimal(std::uint16_t) Konstruktor

Konstruiert eine Instanz, die den angegebenen Wert darstellt.

```cpp
System::Decimal::Decimal(std::uint16_t i)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| i | std::uint16_t | 16-Bit-vorzeichenloser Ganzzahlwert, der vom zu erstellenden [Decimal](../)-Objekt dargestellt wird |

## Decimal::Decimal(std::uint32_t) Konstruktor

Konstruiert eine Instanz, die den angegebenen Wert darstellt.

```cpp
System::Decimal::Decimal(std::uint32_t i)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| i | std::uint32_t | 32-Bit-vorzeichenloser Ganzzahlwert, der vom zu erstellenden [Decimal](../)-Objekt dargestellt wird |

## Decimal::Decimal(std::uint64_t) Konstruktor

Konstruiert eine Instanz, die den angegebenen Wert darstellt.

```cpp
System::Decimal::Decimal(std::uint64_t i)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| i | std::uint64_t | 64-Bit-vorzeichenloser Ganzzahlwert, der vom zu erstellenden [Decimal](../)-Objekt dargestellt wird |

## Decimal::Decimal(float) Konstruktor

Konstruiert eine Instanz, die den angegebenen Wert darstellt.

```cpp
System::Decimal::Decimal(float f)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| f | **float** | Der einzelpräzise Gleitkommawert, der vom zu erstellenden [Decimal](../)-Objekt dargestellt wird |

## Decimal::Decimal(double) Konstruktor

Konstruiert eine Instanz, die den angegebenen Wert darstellt.

```cpp
System::Decimal::Decimal(double d)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| d | **double** | Der doppeltpräzise Gleitkommawert, der vom zu erstellenden [Decimal](../)-Objekt dargestellt wird |

## Decimal::Decimal(const std::string&) Konstruktor

Konstruiert eine Instanz, die einen Wert darstellt, dessen Zeichenkettenrepräsentation als Instanz der Klasse std::string angegeben wird.

```cpp
System::Decimal::Decimal(const std::string &str)
```

## Decimal::Decimal(int32_t, int32_t, int32_t, bool, uint8_t) Konstruktor

Konstruiert ein [Decimal](../)-Objekt aus den angegebenen Komponenten.

```cpp
System::Decimal::Decimal(int32_t lo, int32_t mid, int32_t hi, bool isNegative, uint8_t scale)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lo | **int32_t** | Die niedrigen 32 Bits des Werts |
| mid | **int32_t** | Die mittleren 32 Bits des Werts |
| hi | **int32_t** | Die hohen 32 Bits des Werts |
| isNegative | **bool** | Gibt an, ob der Wert negativ ist |
| scale | **uint8_t** | Eine Potenz von 10 im Bereich von 0 bis 28 |

## Decimal::Decimal(const Decimal&) Konstruktor

Konstruiert eine Instanz der Klasse [Decimal](../), die dieselbe Zahl wie das angegebene [Decimal](../)-Objekt darstellt.

```cpp
System::Decimal::Decimal(const Decimal &d)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| d | const [Decimal](../)& | Ein [Decimal](../)-Objekt, aus dem der Wert kopiert wird |

## Decimal::Decimal(const ArrayPtr<int32_t>&) Konstruktor

Konstruiert eine Instanz der Klasse [Decimal](../) aus einem Integer-Array, das eine binäre Darstellung enthält.

```cpp
System::Decimal::Decimal(const ArrayPtr<int32_t> &bits)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bits | const [ArrayPtr](../../arrayptr/)<**int32_t**>& | Ein Integer-Array, das eine binäre Darstellung enthält. |

## Decimal::Decimal(std::nullptr_t) Konstruktor

Wirft stets ArgumentNullException.

```cpp
System::Decimal::Decimal(std::nullptr_t bits)
```

## Decimal::Decimal(const number_type&) Konstruktor

Konstruiert eine Instanz der Klasse [Decimal](../), die den angegebenen Wert darstellt.

```cpp
System::Decimal::Decimal(const number_type &value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [number_type](../number_type/)& | Eine konstante Referenz auf den Wert, der von dem zu erstellenden Objekt dargestellt wird |

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [number_type](../number_type/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)