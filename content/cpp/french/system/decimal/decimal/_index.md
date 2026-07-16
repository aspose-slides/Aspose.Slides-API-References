---
title: Decimal()
second_title: Référence API Aspose.Slides pour C++
description: Construit une instance qui représente 0.
type: docs
weight: 1
url: /fr/system/decimal/decimal/
---
## Decimal::Decimal() constructeur

Construit une instance qui représente 0.

```cpp
System::Decimal::Decimal()
```

## Decimal::Decimal(std::int8_t) constructeur

Construit une instance qui représente la valeur spécifiée.

```cpp
System::Decimal::Decimal(std::int8_t i)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| i | std::int8_t | Valeur entière de 8 bits à représenter par l'objet [Decimal](../) en cours de construction |

## Decimal::Decimal(std::int16_t) constructeur

Construit une instance qui représente la valeur spécifiée.

```cpp
System::Decimal::Decimal(std::int16_t i)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| i | std::int16_t | Valeur entière de 16 bits à représenter par l'objet [Decimal](../) en cours de construction |

## Decimal::Decimal(std::int32_t) constructeur

Construit une instance qui représente la valeur spécifiée.

```cpp
System::Decimal::Decimal(std::int32_t i)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| i | std::int32_t | Valeur entière de 32 bits à représenter par l'objet [Decimal](../) en cours de construction |

## Decimal::Decimal(std::int64_t) constructeur

Construit une instance qui représente la valeur spécifiée.

```cpp
System::Decimal::Decimal(std::int64_t i)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| i | std::int64_t | Valeur entière de 64 bits à représenter par l'objet [Decimal](../) en cours de construction |

## Decimal::Decimal(std::uint8_t) constructeur

Construit une instance qui représente la valeur spécifiée.

```cpp
System::Decimal::Decimal(std::uint8_t i)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| i | std::uint8_t | Valeur entière non signée de 8 bits à représenter par l'objet [Decimal](../) en cours de construction |

## Decimal::Decimal(std::uint16_t) constructeur

Construit une instance qui représente la valeur spécifiée.

```cpp
System::Decimal::Decimal(std::uint16_t i)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| i | std::uint16_t | Valeur entière non signée de 16 bits à représenter par l'objet [Decimal](../) en cours de construction |

## Decimal::Decimal(std::uint32_t) constructeur

Construit une instance qui représente la valeur spécifiée.

```cpp
System::Decimal::Decimal(std::uint32_t i)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| i | std::uint32_t | Valeur entière non signée de 32 bits à représenter par l'objet [Decimal](../) en cours de construction |

## Decimal::Decimal(std::uint64_t) constructeur

Construit une instance qui représente la valeur spécifiée.

```cpp
System::Decimal::Decimal(std::uint64_t i)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| i | std::uint64_t | Valeur entière non signée de 64 bits à représenter par l'objet [Decimal](../) en cours de construction |

## Decimal::Decimal(float) constructeur

Construit une instance qui représente la valeur spécifiée.

```cpp
System::Decimal::Decimal(float f)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| f | **float** | Valeur à virgule flottante simple précision à représenter par l'objet [Decimal](../) en cours de construction |

## Decimal::Decimal(double) constructeur

Construit une instance qui représente la valeur spécifiée.

```cpp
System::Decimal::Decimal(double d)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| d | **double** | Valeur à virgule flottante double précision à représenter par l'objet [Decimal](../) en cours de construction |

## Decimal::Decimal(const std::string\&) constructeur

Construit une instance qui représente une valeur dont la représentation sous forme de chaîne est spécifiée comme une instance de la classe std::string.

```cpp
System::Decimal::Decimal(const std::string &str)
```

## Decimal::Decimal(int32_t, int32_t, int32_t, bool, uint8_t) constructeur

Construit un objet [Decimal](../) à partir des composants spécifiés.

```cpp
System::Decimal::Decimal(int32_t lo, int32_t mid, int32_t hi, bool isNegative, uint8_t scale)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lo | **int32_t** | Les 32 bits de poids faible de la valeur |
| mid | **int32_t** | Les 32 bits du milieu de la valeur |
| hi | **int32_t** | Les 32 bits de poids fort de la valeur |
| isNegative | **bool** | Indique si la valeur est négative |
| scale | **uint8_t** | Une puissance de 10 allant de 0 à 28 |

## Decimal::Decimal(const Decimal\&) constructeur

Construit une instance de la classe [Decimal](../) qui représente le même nombre que l'objet [Decimal](../) spécifié.

```cpp
System::Decimal::Decimal(const Decimal &d)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../)\& | Un objet [Decimal](../) dont la valeur est copiée |

## Decimal::Decimal(const ArrayPtr\<int32_t\>\&) constructeur

Construit une instance de la classe [Decimal](../) à partir d'un tableau d'entiers contenant une représentation binaire.

```cpp
System::Decimal::Decimal(const ArrayPtr<int32_t> &bits)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bits | const [ArrayPtr](../../arrayptr/)\<**int32_t**\>\& | Un tableau d'entiers contenant une représentation binaire. |

## Decimal::Decimal(std::nullptr_t) constructeur

Lance toujours ArgumentNullException.

```cpp
System::Decimal::Decimal(std::nullptr_t bits)
```

## Decimal::Decimal(const number_type\&) constructeur

Construit une instance de la classe [Decimal](../) représentant la valeur spécifiée.

```cpp
System::Decimal::Decimal(const number_type &value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [number_type](../number_type/)\& | Une référence constante à la valeur à représenter par l'objet en cours de construction |

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [number_type](../number_type/)
* Classe [Decimal](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)