---
title: Compare()
second_title: Aspose.Slides per C++ Riferimento API
description: Confronta due sottostringhe restituendo un valore minore, uguale o maggiore.
type: docs
weight: 820
url: /it/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) metodo

Confronta due sottostringhe restituendo un valore minore, uguale o maggiore.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| strA | const [String](../)\& | Prima stringa da confrontare. |
| indexA | int | Inizio della prima sottostringa. |
| strB | const [String](../)\& | Seconda stringa da confrontare. |
| indexB | int | Inizio della seconda sottostringa. |
| length | int | Numero di caratteri da confrontare. |
| ignoreCase | **bool** | Specifica se il confronto è sensibile al maiuscolo/minuscolo. |

### Valore restituito

Valore negativo se la prima sottostringa è minore della seconda, zero se corrispondono, valore positivo altrimenti.

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) metodo

Confronta due sottostringhe restituendo un valore minore, uguale o maggiore.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| strA | const [String](../)\& | Prima stringa da confrontare. |
| indexA | int | Inizio della prima sottostringa. |
| strB | const [String](../)\& | Seconda stringa da confrontare. |
| indexB | int | Inizio della seconda sottostringa. |
| length | int | Numero di caratteri da confrontare. |
| ignoreCase | **bool** | Specifica se il confronto è sensibile al maiuscolo/minuscolo. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura da utilizzare per il confronto. |

### Valore restituito

Valore negativo se la prima sottostringa è minore della seconda, zero se corrispondono, valore positivo altrimenti.

## String::Compare(const String\&, const String\&, System::StringComparison) metodo

Confronta due stringhe restituendo un valore minore, uguale o maggiore.

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| strA | const [String](../)\& | Prima stringa da confrontare. |
| strB | const [String](../)\& | Seconda stringa da confrontare. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modalità. |

### Valore restituito

Valore negativo se la prima sottostringa è minore della seconda, zero se corrispondono, valore positivo altrimenti.

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) metodo

Confronta due stringhe restituendo un valore minore, uguale o maggiore.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| strA | const [String](../)\& | Prima stringa da confrontare. |
| indexA | int | Inizio della prima sottostringa. |
| strB | const [String](../)\& | Seconda stringa da confrontare. |
| indexB | int | Inizio della seconda sottostringa. |
| length | int | Numero di caratteri da confrontare. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modalità. |

### Valore restituito

Valore negativo se la prima sottostringa è minore della seconda, zero se corrispondono, valore positivo altrimenti.

## String::Compare(const String\&, const String\&, bool) metodo

Confronta due stringhe restituendo un valore minore, uguale o maggiore.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| strA | const [String](../)\& | Prima stringa da confrontare. |
| strB | const [String](../)\& | Seconda stringa da confrontare. |
| ignoreCase | **bool** | Specifica se il confronto è sensibile al maiuscolo/minuscolo. |

### Valore restituito

Valore negativo se la prima sottostringa è minore della seconda, zero se corrispondono, valore positivo altrimenti.

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) metodo

Confronta due stringhe restituendo un valore minore, uguale o maggiore.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| strA | const [String](../)\& | Prima stringa da confrontare. |
| strB | const [String](../)\& | Seconda stringa da confrontare. |
| ignoreCase | **bool** | Specifica se il confronto è sensibile al maiuscolo/minuscolo. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura da utilizzare per il confronto. |

### Valore restituito

Valore negativo se la prima sottostringa è minore della seconda, zero se corrispondono, valore positivo altrimenti.

## Vedi anche

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)