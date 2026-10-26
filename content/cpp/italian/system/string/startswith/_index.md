---
title: StartsWith()
second_title: Riferimento API Aspose.Slides per C++
description: Verifica se la stringa inizia con la sottostringa specificata.
type: docs
weight: 469
url: /it/system/string/startswith/
---
## String::StartsWith(const String\&) const method

Verifica se la stringa inizia con la sottostringa specificata.

```cpp
bool System::String::StartsWith(const String &value) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../)\& | Stringa di ricerca. |

### Valore di ritorno

true se la stringa inizia con la sottostringa specificata, false altrimenti.

## String::StartsWith(const String\&, System::StringComparison) const method

Verifica se la stringa inizia con la sottostringa specificata.

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../)\& | Stringa di ricerca. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode, see [System::StringComparison](../../stringcomparison/) for details. |

### Valore di ritorno

true se la stringa inizia con la sottostringa specificata, false altrimenti.

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const method

Verifica se la stringa inizia con la sottostringa specificata.

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../)\& | Stringa di ricerca. |
| ignoreCase | **bool** | Specifica se il confronto è case-insensitive. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura da utilizzare durante il confronto della stringa. |

### Valore di ritorno

true se la stringa inizia con la sottostringa specificata, false altrimenti.

## Vedi anche

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)