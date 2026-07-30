---
title: Decimal()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un'istanza che rappresenta 0.
type: docs
weight: 1
url: /it/system/decimal/decimal/
---
## Decimal::Decimal() costruttore


Crea un'istanza che rappresenta 0.

```cpp
System::Decimal::Decimal()
```

## Decimal::Decimal(std::int8_t) costruttore


Crea un'istanza che rappresenta il valore specificato.

```cpp
System::Decimal::Decimal(std::int8_t i)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| i | std::int8_t | Valore intero a 8 bit da rappresentare dall'oggetto [Decimal](../) in costruzione |

## Decimal::Decimal(std::int16_t) costruttore


Crea un'istanza che rappresenta il valore specificato.

```cpp
System::Decimal::Decimal(std::int16_t i)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| i | std::int16_t | Valore intero a 16 bit da rappresentare dall'oggetto [Decimal](../) in costruzione |

## Decimal::Decimal(std::int32_t) costruttore


Crea un'istanza che rappresenta il valore specificato.

```cpp
System::Decimal::Decimal(std::int32_t i)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| i | std::int32_t | Valore intero a 32 bit da rappresentare dall'oggetto [Decimal](../) in costruzione |

## Decimal::Decimal(std::int64_t) costruttore


Crea un'istanza che rappresenta il valore specificato.

```cpp
System::Decimal::Decimal(std::int64_t i)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| i | std::int64_t | Valore intero a 64 bit da rappresentare dall'oggetto [Decimal](../) in costruzione |

## Decimal::Decimal(std::uint8_t) costruttore


Crea un'istanza che rappresenta il valore specificato.

```cpp
System::Decimal::Decimal(std::uint8_t i)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| i | std::uint8_t | Valore intero senza segno a 8 bit da rappresentare dall'oggetto [Decimal](../) in costruzione |

## Decimal::Decimal(std::uint16_t) costruttore


Crea un'istanza che rappresenta il valore specificato.

```cpp
System::Decimal::Decimal(std::uint16_t i)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| i | std::uint16_t | Valore intero senza segno a 16 bit da rappresentare dall'oggetto [Decimal](../) in costruzione |

## Decimal::Decimal(std::uint32_t) costruttore


Crea un'istanza che rappresenta il valore specificato.

```cpp
System::Decimal::Decimal(std::uint32_t i)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| i | std::uint32_t | Valore intero senza segno a 32 bit da rappresentare dall'oggetto [Decimal](../) in costruzione |

## Decimal::Decimal(std::uint64_t) costruttore


Crea un'istanza che rappresenta il valore specificato.

```cpp
System::Decimal::Decimal(std::uint64_t i)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| i | std::uint64_t | Valore intero senza segno a 64 bit da rappresentare dall'oggetto [Decimal](../) in costruzione |

## Decimal::Decimal(float) costruttore


Crea un'istanza che rappresenta il valore specificato.

```cpp
System::Decimal::Decimal(float f)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| f | **float** | Valore a virgola mobile a precisione singola da rappresentare dall'oggetto [Decimal](../) in costruzione |

## Decimal::Decimal(double) costruttore


Crea un'istanza che rappresenta il valore specificato.

```cpp
System::Decimal::Decimal(double d)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| d | **double** | Valore a virgola mobile a doppia precisione da rappresentare dall'oggetto [Decimal](../) in costruzione |

## Decimal::Decimal(const std::string\&) costruttore


Crea un'istanza che rappresenta un valore la cui rappresentazione in stringa è specificata come istanza della classe std::string.

```cpp
System::Decimal::Decimal(const std::string &str)
```

## Decimal::Decimal(int32_t, int32_t, int32_t, bool, uint8_t) costruttore


Crea un oggetto [Decimal](../) dai componenti specificati.

```cpp
System::Decimal::Decimal(int32_t lo, int32_t mid, int32_t hi, bool isNegative, uint8_t scale)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lo | **int32_t** | I 32 bit più bassi del valore |
| mid | **int32_t** | I 32 bit centrali del valore |
| hi | **int32_t** | I 32 bit più alti del valore |
| isNegative | **bool** | Indica se il valore è negativo |
| scale | **uint8_t** | Una potenza di 10 compresa tra 0 e 28 |

## Decimal::Decimal(const Decimal\&) costruttore


Crea un'istanza della classe [Decimal](../) che rappresenta lo stesso numero dell'oggetto [Decimal](../) specificato.

```cpp
System::Decimal::Decimal(const Decimal &d)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| d | const [Decimal](../)\& | Un oggetto [Decimal](../) da cui copiare il valore |

## Decimal::Decimal(const ArrayPtr\<int32_t\>\&) costruttore


Crea un'istanza della classe [Decimal](../) da un array di interi contenente una rappresentazione binaria.

```cpp
System::Decimal::Decimal(const ArrayPtr<int32_t> &bits)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bits | const [ArrayPtr](../../arrayptr/)\<**int32_t**\>\& | Un array di interi contenente una rappresentazione binaria. |

## Decimal::Decimal(std::nullptr_t) costruttore


Genera sempre un'eccezione ArgumentNullException.

```cpp
System::Decimal::Decimal(std::nullptr_t bits)
```

## Decimal::Decimal(const number_type\&) costruttore


Crea un'istanza della classe [Decimal](../) che rappresenta il valore specificato.

```cpp
System::Decimal::Decimal(const number_type &value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [number_type](../number_type/)\& | Un riferimento costante al valore da rappresentare dall'oggetto in costruzione |

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [number_type](../number_type/)
* Classe [Decimal](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)