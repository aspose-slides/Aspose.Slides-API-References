---
title: Decimal()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy instancję reprezentującą 0.
type: docs
weight: 1
url: /pl/system/decimal/decimal/
---
## Decimal::Decimal() konstruktor

Tworzy instancję, która reprezentuje 0.

```cpp
System::Decimal::Decimal()
```

## Decimal::Decimal(std::int8_t) konstruktor

Tworzy instancję, która reprezentuje podaną wartość.

```cpp
System::Decimal::Decimal(std::int8_t i)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::int8_t | 8-bitowa wartość całkowita, która ma być reprezentowana przez obiekt [Decimal](../) tworzony |

## Decimal::Decimal(std::int16_t) konstruktor

Tworzy instancję, która reprezentuje podaną wartość.

```cpp
System::Decimal::Decimal(std::int16_t i)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::int16_t | 16-bitowa wartość całkowita, która ma być reprezentowana przez obiekt [Decimal](../) tworzony |

## Decimal::Decimal(std::int32_t) konstruktor

Tworzy instancję, która reprezentuje podaną wartość.

```cpp
System::Decimal::Decimal(std::int32_t i)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::int32_t | 32-bitowa wartość całkowita, która ma być reprezentowana przez obiekt [Decimal](../) tworzony |

## Decimal::Decimal(std::int64_t) konstruktor

Tworzy instancję, która reprezentuje podaną wartość.

```cpp
System::Decimal::Decimal(std::int64_t i)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::int64_t | 64-bitowa wartość całkowita, która ma być reprezentowana przez obiekt [Decimal](../) tworzony |

## Decimal::Decimal(std::uint8_t) konstruktor

Tworzy instancję, która reprezentuje podaną wartość.

```cpp
System::Decimal::Decimal(std::uint8_t i)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::uint8_t | nieoznakowana 8-bitowa wartość całkowita, która ma być reprezentowana przez obiekt [Decimal](../) tworzony |

## Decimal::Decimal(std::uint16_t) konstruktor

Tworzy instancję, która reprezentuje podaną wartość.

```cpp
System::Decimal::Decimal(std::uint16_t i)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::uint16_t | nieoznakowana 16-bitowa wartość całkowita, która ma być reprezentowana przez obiekt [Decimal](../) tworzony |

## Decimal::Decimal(std::uint32_t) konstruktor

Tworzy instancję, która reprezentuje podaną wartość.

```cpp
System::Decimal::Decimal(std::uint32_t i)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::uint32_t | nieoznakowana 32-bitowa wartość całkowita, która ma być reprezentowana przez obiekt [Decimal](../) tworzony |

## Decimal::Decimal(std::uint64_t) konstruktor

Tworzy instancję, która reprezentuje podaną wartość.

```cpp
System::Decimal::Decimal(std::uint64_t i)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::uint64_t | nieoznakowana 64-bitowa wartość całkowita, która ma być reprezentowana przez obiekt [Decimal](../) tworzony |

## Decimal::Decimal(float) konstruktor

Tworzy instancję, która reprezentuje podaną wartość.

```cpp
System::Decimal::Decimal(float f)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| f | **float** | Wartość zmiennoprzecinkowa pojedynczej precyzji, która ma być reprezentowana przez obiekt [Decimal](../) tworzony |

## Decimal::Decimal(double) konstruktor

Tworzy instancję, która reprezentuje podaną wartość.

```cpp
System::Decimal::Decimal(double d)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| d | **double** | Wartość zmiennoprzecinkowa podwójnej precyzji, która ma być reprezentowana przez obiekt [Decimal](../) tworzony |

## Decimal::Decimal(const std::string\&) konstruktor

Tworzy instancję, która reprezentuje wartość, której reprezentacja tekstowa jest podana jako instancja klasy std::string.

```cpp
System::Decimal::Decimal(const std::string &str)
```

## Decimal::Decimal(int32_t, int32_t, int32_t, bool, uint8_t) konstruktor

Tworzy obiekt [Decimal](../) z podanych składników.

```cpp
System::Decimal::Decimal(int32_t lo, int32_t mid, int32_t hi, bool isNegative, uint8_t scale)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| lo | **int32_t** | Dolne 32 bity wartości |
| mid | **int32_t** | Środkowe 32 bity wartości |
| hi | **int32_t** | Górne 32 bity wartości |
| isNegative | **bool** | Określa, czy wartość jest ujemna |
| scale | **uint8_t** | Potęga 10 w przedziale od 0 do 28 |

## Decimal::Decimal(const Decimal\&) konstruktor

Tworzy instancję klasy [Decimal](../), która reprezentuje tę samą liczbę co podany obiekt [Decimal](../).

```cpp
System::Decimal::Decimal(const Decimal &d)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../)\& | Obiekt [Decimal](../), z którego kopiowana jest wartość |

## Decimal::Decimal(const ArrayPtr\<int32_t\>\&) konstruktor

Tworzy instancję klasy [Decimal](../) z tablicy całkowitoliczbowej zawierającej reprezentację binarną.

```cpp
System::Decimal::Decimal(const ArrayPtr<int32_t> &bits)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bits | const [ArrayPtr](../../arrayptr/)\<**int32_t**\>\& | Tablica całkowitoliczbowej zawierająca reprezentację binarną. |

## Decimal::Decimal(std::nullptr_t) konstruktor

Zawsze zgłasza wyjątek ArgumentNullException.

```cpp
System::Decimal::Decimal(std::nullptr_t bits)
```

## Decimal::Decimal(const number_type\&) konstruktor

Tworzy instancję klasy [Decimal](../) reprezentującą podaną wartość.

```cpp
System::Decimal::Decimal(const number_type &value)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [number_type](../number_type/)\& | Stałe odwołanie do wartości, którą ma reprezentować tworzony obiekt |

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [number_type](../number_type/)
* Klasa [Decimal](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)