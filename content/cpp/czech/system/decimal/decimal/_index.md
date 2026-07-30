---
title: Decimal()
second_title: Aspose.Slides pro C++ - reference API
description: Vytvoří instanci, která představuje 0.
type: docs
weight: 1
url: /cs/system/decimal/decimal/
---
## Decimal::Decimal() konstruktor

Vytvoří instanci, která představuje 0.

```cpp
System::Decimal::Decimal()
```

## Decimal::Decimal(std::int8_t) konstruktor

Vytvoří instanci, která představuje zadanou hodnotu.

```cpp
System::Decimal::Decimal(std::int8_t i)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| i | std::int8_t | 8-bitová celočíselná hodnota, kterou bude reprezentovat objekt [Decimal](../) při konstrukci |

## Decimal::Decimal(std::int16_t) konstruktor

Vytvoří instanci, která představuje zadanou hodnotu.

```cpp
System::Decimal::Decimal(std::int16_t i)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| i | std::int16_t | 16-bitová celočíselná hodnota, kterou bude reprezentovat objekt [Decimal](../) při konstrukci |

## Decimal::Decimal(std::int32_t) konstruktor

Vytvoří instanci, která představuje zadanou hodnotu.

```cpp
System::Decimal::Decimal(std::int32_t i)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| i | std::int32_t | 32-bitová celočíselná hodnota, kterou bude reprezentovat objekt [Decimal](../) při konstrukci |

## Decimal::Decimal(std::int64_t) konstruktor

Vytvoří instanci, která představuje zadanou hodnotu.

```cpp
System::Decimal::Decimal(std::int64_t i)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| i | std::int64_t | 64-bitová celočíselná hodnota, kterou bude reprezentovat objekt [Decimal](../) při konstrukci |

## Decimal::Decimal(std::uint8_t) konstruktor

Vytvoří instanci, která představuje zadanou hodnotu.

```cpp
System::Decimal::Decimal(std::uint8_t i)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| i | std::uint8_t | bezznaménková 8-bitová celočíselná hodnota, kterou bude reprezentovat objekt [Decimal](../) při konstrukci |

## Decimal::Decimal(std::uint16_t) konstruktor

Vytvoří instanci, která představuje zadanou hodnotu.

```cpp
System::Decimal::Decimal(std::uint16_t i)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| i | std::uint16_t | bezznaménková 16-bitová celočíselná hodnota, kterou bude reprezentovat objekt [Decimal](../) při konstrukci |

## Decimal::Decimal(std::uint32_t) konstruktor

Vytvoří instanci, která představuje zadanou hodnotu.

```cpp
System::Decimal::Decimal(std::uint32_t i)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| i | std::uint32_t | bezznaménková 32-bitová celočíselná hodnota, kterou bude reprezentovat objekt [Decimal](../) při konstrukci |

## Decimal::Decimal(std::uint64_t) konstruktor

Vytvoří instanci, která představuje zadanou hodnotu.

```cpp
System::Decimal::Decimal(std::uint64_t i)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| i | std::uint64_t | bezznaménková 64-bitová celočíselná hodnota, kterou bude reprezentovat objekt [Decimal](../) při konstrukci |

## Decimal::Decimal(float) konstruktor

Vytvoří instanci, která představuje zadanou hodnotu.

```cpp
System::Decimal::Decimal(float f)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| f | **float** | Hodnota s jednoduchou přesností typu float, kterou bude reprezentovat objekt [Decimal](../) při konstrukci |

## Decimal::Decimal(double) konstruktor

Vytvoří instanci, která představuje zadanou hodnotu.

```cpp
System::Decimal::Decimal(double d)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| d | **double** | Hodnota s dvojitou přesností typu double, kterou bude reprezentovat objekt [Decimal](../) při konstrukci |

## Decimal::Decimal(const std::string&) konstruktor

Vytvoří instanci, která představuje hodnotu, jejíž řetězcová reprezentace je zadána jako instance třídy std::string.

```cpp
System::Decimal::Decimal(const std::string &str)
```

## Decimal::Decimal(int32_t, int32_t, int32_t, bool, uint8_t) konstruktor

Vytvoří objekt [Decimal](../) ze zadaných komponent.

```cpp
System::Decimal::Decimal(int32_t lo, int32_t mid, int32_t hi, bool isNegative, uint8_t scale)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lo | **int32_t** | Nízkých 32 bitů hodnoty |
| mid | **int32_t** | Středních 32 bitů hodnoty |
| hi | **int32_t** | Vysokých 32 bitů hodnoty |
| isNegative | **bool** | Určuje, zda je hodnota záporná |
| scale | **uint8_t** | Mocnina deseti v rozmezí 0 – 28 |

## Decimal::Decimal(const Decimal&) konstruktor

Vytvoří instanci třídy [Decimal](../), která představuje stejné číslo jako zadaný objekt [Decimal](../).

```cpp
System::Decimal::Decimal(const Decimal &d)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| d | const [Decimal](../)\& | Objekt [Decimal](../), ze kterého se kopíruje hodnota |

## Decimal::Decimal(const ArrayPtr<int32_t>&) konstruktor

Vytvoří instanci třídy [Decimal](../) z celočíselného pole obsahujícího binární reprezentaci.

```cpp
System::Decimal::Decimal(const ArrayPtr<int32_t> &bits)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bits | const [ArrayPtr](../../arrayptr/)<**int32_t**>\& | Celočíselné pole obsahující binární reprezentaci. |

## Decimal::Decimal(std::nullptr_t) konstruktor

Vždy vyvolá výjimku ArgumentNullException.

```cpp
System::Decimal::Decimal(std::nullptr_t bits)
```

## Decimal::Decimal(const number_type&) konstruktor

Vytvoří instanci třídy [Decimal](../), která představuje zadanou hodnotu.

```cpp
System::Decimal::Decimal(const number_type &value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [number_type](../number_type/)\& | Konstantní reference na hodnotu, kterou má reprezentovat objekt při konstrukci |

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [number_type](../number_type/)
* Třída [Decimal](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)