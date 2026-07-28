---
title: Decimal()
second_title: Aspose.Slides C++ API-referencia
description: Létrehoz egy példányt, amely a 0-t reprezentálja.
type: docs
weight: 1
url: /hu/system/decimal/decimal/
---
## Decimal::Decimal() konstruktor

Létrehoz egy példányt, amely a 0-t reprezentálja.

```cpp
System::Decimal::Decimal()
```

## Decimal::Decimal(std::int8_t) konstruktor

Létrehoz egy példányt, amely a megadott értéket reprezentálja.

```cpp
System::Decimal::Decimal(std::int8_t i)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| i | std::int8_t | 8 bites egész érték, amelyet a létrehozott [Decimal](../) objektum reprezentál. |

## Decimal::Decimal(std::int16_t) konstruktor

Létrehoz egy példányt, amely a megadott értéket reprezentálja.

```cpp
System::Decimal::Decimal(std::int16_t i)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| i | std::int16_t | 16 bites egész érték, amelyet a létrehozott [Decimal](../) objektum reprezentál. |

## Decimal::Decimal(std::int32_t) konstruktor

Létrehoz egy példányt, amely a megadott értéket reprezentálja.

```cpp
System::Decimal::Decimal(std::int32_t i)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| i | std::int32_t | 32 bites egész érték, amelyet a létrehozott [Decimal](../) objektum reprezentál. |

## Decimal::Decimal(std::int64_t) konstruktor

Létrehoz egy példányt, amely a megadott értéket reprezentálja.

```cpp
System::Decimal::Decimal(std::int64_t i)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| i | std::int64_t | 64 bites egész érték, amelyet a létrehozott [Decimal](../) objektum reprezentál. |

## Decimal::Decimal(std::uint8_t) konstruktor

Létrehoz egy példányt, amely a megadott értéket reprezentálja.

```cpp
System::Decimal::Decimal(std::uint8_t i)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| i | std::uint8_t | 8 bites előjelnélküli egész érték, amelyet a létrehozott [Decimal](../) objektum reprezentál. |

## Decimal::Decimal(std::uint16_t) konstruktor

Létrehoz egy példányt, amely a megadott értéket reprezentálja.

```cpp
System::Decimal::Decimal(std::uint16_t i)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| i | std::uint16_t | 16 bites előjelnélküli egész érték, amelyet a létrehozott [Decimal](../) objektum reprezentál. |

## Decimal::Decimal(std::uint32_t) konstruktor

Létrehoz egy példányt, amely a megadott értéket reprezentálja.

```cpp
System::Decimal::Decimal(std::uint32_t i)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| i | std::uint32_t | 32 bites előjelnélküli egész érték, amelyet a létrehozott [Decimal](../) objektum reprezentál. |

## Decimal::Decimal(std::uint64_t) konstruktor

Létrehoz egy példányt, amely a megadott értéket reprezentálja.

```cpp
System::Decimal::Decimal(std::uint64_t i)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| i | std::uint64_t | 64 bites előjelnélküli egész érték, amelyet a létrehozott [Decimal](../) objektum reprezentál. |

## Decimal::Decimal(float) konstruktor

Létrehoz egy példányt, amely a megadott értéket reprezentálja.

```cpp
System::Decimal::Decimal(float f)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| f | **float** | Az egyszeres pontosságú lebegőpontos érték, amelyet a létrehozott [Decimal](../) objektum reprezentál. |

## Decimal::Decimal(double) konstruktor

Létrehoz egy példányt, amely a megadott értéket reprezentálja.

```cpp
System::Decimal::Decimal(double d)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| d | **double** | A dupla pontosságú lebegőpontos érték, amelyet a létrehozott [Decimal](../) objektum reprezentál. |

## Decimal::Decimal(const std::string\&) konstruktor

Létrehoz egy példányt, amelynek karakterláncábrázolása a std::string osztály egy példányaként van megadva.

```cpp
System::Decimal::Decimal(const std::string &str)
```

## Decimal::Decimal(int32_t, int32_t, int32_t, bool, uint8_t) konstruktor

Létrehoz egy [Decimal](../) objektumot a megadott komponensekből.

```cpp
System::Decimal::Decimal(int32_t lo, int32_t mid, int32_t hi, bool isNegative, uint8_t scale)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lo | **int32_t** | Az érték alsó 32 bitje |
| mid | **int32_t** | Az érték középső 32 bitje |
| hi | **int32_t** | Az érték felső 32 bitje |
| isNegative | **bool** | Meghatározza, hogy az érték negatív-e |
| scale | **uint8_t** | 0-tól 28-ig terjedő 10-es hatvány |

## Decimal::Decimal(const Decimal\&) konstruktor

Létrehoz egy [Decimal](../) osztályú példányt, amely ugyanazt a számot reprezentálja, mint a megadott [Decimal](../) objektum.

```cpp
System::Decimal::Decimal(const Decimal &d)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| d | const [Decimal](../)\& | Egy [Decimal](../) objektum, amelyből az érték másolódik. |

## Decimal::Decimal(const ArrayPtr\<int32_t\>\&) konstruktor

Létrehoz egy [Decimal](../) osztályú példányt egy bináris ábrázolást tartalmazó egész szám tömbből.

```cpp
System::Decimal::Decimal(const ArrayPtr<int32_t> &bits)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bits | const [ArrayPtr](../../arrayptr/)\<**int32_t**\>\& | Egy egész szám tömb, amely bináris ábrázolást tartalmaz. |

## Decimal::Decimal(std::nullptr_t) konstruktor

Mindig ArgumentNullException-t dob.

```cpp
System::Decimal::Decimal(std::nullptr_t bits)
```

## Decimal::Decimal(const number_type\&) konstruktor

Létrehoz egy [Decimal](../) osztályú példányt, amely a megadott értéket reprezentálja.

```cpp
System::Decimal::Decimal(const number_type &value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [number_type](../number_type/)\& | Egy konstans referenciája annak az értéknek, amelyet a létrehozott objektum reprezentál. |

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [number_type](../number_type/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)