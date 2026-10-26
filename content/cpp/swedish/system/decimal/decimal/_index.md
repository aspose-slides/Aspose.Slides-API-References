---
title: Decimal()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en instans som representerar 0.
type: docs
weight: 1
url: /sv/system/decimal/decimal/
---
## Decimal::Decimal() konstruktor


Skapar en instans som representerar 0.

```cpp
System::Decimal::Decimal()
```

## Decimal::Decimal(std::int8_t) konstruktor


Skapar en instans som representerar det angivna värdet.

```cpp
System::Decimal::Decimal(std::int8_t i)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | std::int8_t | 8-bitars heltalsvärde som ska representeras av [Decimal](../)-objektet som konstrueras |

## Decimal::Decimal(std::int16_t) konstruktor


Skapar en instans som representerar det angivna värdet.

```cpp
System::Decimal::Decimal(std::int16_t i)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | std::int16_t | 16-bitars heltalsvärde som ska representeras av [Decimal](../)-objektet som konstrueras |

## Decimal::Decimal(std::int32_t) konstruktor


Skapar en instans som representerar det angivna värdet.

```cpp
System::Decimal::Decimal(std::int32_t i)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | std::int32_t | 32-bitars heltalsvärde som ska representeras av [Decimal](../)-objektet som konstrueras |

## Decimal::Decimal(std::int64_t) konstruktor


Skapar en instans som representerar det angivna värdet.

```cpp
System::Decimal::Decimal(std::int64_t i)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | std::int64_t | 64-bitars heltalsvärde som ska representeras av [Decimal](../)-objektet som konstrueras |

## Decimal::Decimal(std::uint8_t) konstruktor


Skapar en instans som representerar det angivna värdet.

```cpp
System::Decimal::Decimal(std::uint8_t i)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | std::uint8_t | osignerat 8-bitars heltalsvärde som ska representeras av [Decimal](../)-objektet som konstrueras |

## Decimal::Decimal(std::uint16_t) konstruktor


Skapar en instans som representerar det angivna värdet.

```cpp
System::Decimal::Decimal(std::uint16_t i)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | std::uint16_t | osignerat 16-bitars heltalsvärde som ska representeras av [Decimal](../)-objektet som konstrueras |

## Decimal::Decimal(std::uint32_t) konstruktor


Skapar en instans som representerar det angivna värdet.

```cpp
System::Decimal::Decimal(std::uint32_t i)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | std::uint32_t | osignerat 32-bitars heltalsvärde som ska representeras av [Decimal](../)-objektet som konstrueras |

## Decimal::Decimal(std::uint64_t) konstruktor


Skapar en instans som representerar det angivna värdet.

```cpp
System::Decimal::Decimal(std::uint64_t i)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | std::uint64_t | osignerat 64-bitars heltalsvärde som ska representeras av [Decimal](../)-objektet som konstrueras |

## Decimal::Decimal(float) konstruktor


Skapar en instans som representerar det angivna värdet.

```cpp
System::Decimal::Decimal(float f)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| f | **float** | Det enkelprecisions flyttal som ska representeras av [Decimal](../)-objektet som konstrueras |

## Decimal::Decimal(double) konstruktor


Skapar en instans som representerar det angivna värdet.

```cpp
System::Decimal::Decimal(double d)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| d | **double** | Det dubbelprecisions flyttal som ska representeras av [Decimal](../)-objektet som konstrueras |

## Decimal::Decimal(const std::string\&) konstruktor


Skapar en instans som representerar ett värde vars strängrepresentation specificeras som en instans av std::string-klassen.

```cpp
System::Decimal::Decimal(const std::string &str)
```

## Decimal::Decimal(int32_t, int32_t, int32_t, bool, uint8_t) konstruktor


Skapar ett [Decimal](../)-objekt från de angivna komponenterna.

```cpp
System::Decimal::Decimal(int32_t lo, int32_t mid, int32_t hi, bool isNegative, uint8_t scale)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lo | **int32_t** | De lägsta 32 bitarna av värdet |
| mid | **int32_t** | De mittersta 32 bitarna av värdet |
| hi | **int32_t** | De högsta 32 bitarna av värdet |
| isNegative | **bool** | Anger om värdet är negativt |
| scale | **uint8_t** | En tiopotens som varierar från 0 till 28 |

## Decimal::Decimal(const Decimal\&) konstruktor


Skapar en instans av klassen [Decimal](../) som representerar samma tal som det angivna [Decimal](../)-objektet.

```cpp
System::Decimal::Decimal(const Decimal &d)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| d | const [Decimal](../)\& | Ett [Decimal](../)-objekt att kopiera värdet från |

## Decimal::Decimal(const ArrayPtr\<int32_t\>\&) konstruktor


Skapar en instans av klassen [Decimal](../) från en heltalsarray som innehåller en binär representation.

```cpp
System::Decimal::Decimal(const ArrayPtr<int32_t> &bits)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bits | const [ArrayPtr](../../arrayptr/)\<**int32_t**\>\& | En heltalsarray som innehåller en binär representation. |

## Decimal::Decimal(std::nullptr_t) konstruktor


Kastar alltid ArgumentNullException.

```cpp
System::Decimal::Decimal(std::nullptr_t bits)
```

## Decimal::Decimal(const number_type\&) konstruktor


Skapar en instans av klassen [Decimal](../) som representerar det angivna värdet.

```cpp
System::Decimal::Decimal(const number_type &value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [number_type](../number_type/)\& | En konstant referens till värdet som ska representeras av det konstruerade objektet |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [number_type](../number_type/)
* Klass [Decimal](../)
* Namnrymd [System](../../)
* Library [Aspose.Slides](../../../)