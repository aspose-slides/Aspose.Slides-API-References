---
title: EndsWith()
second_title: Riferimento API Aspose.Slides per C++
description: Verifica se la stringa termina con la sottostringa specificata.
type: docs
weight: 482
url: /it/system/string/endswith/
---
## String::EndsWith(const String\&) const metodo


Controlla se la stringa termina con la sottostringa specificata.

```cpp
bool System::String::EndsWith(const String &value) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../)\& | Stringa di ricerca. |

### Valore restituito

true se la stringa termina con la sottostringa specificata, false altrimenti.

## String::EndsWith(const String\&, System::StringComparison) const metodo


Controlla se la stringa termina con la sottostringa specificata.

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../)\& | Stringa di ricerca. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modalità, vedere [System::StringComparison](../../stringcomparison/) per i dettagli. |

### Valore restituito

true se la stringa termina con la sottostringa specificata, false altrimenti.

## String::EndsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const metodo


Controlla se la stringa termina con la sottostringa specificata.

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../)\& | Stringa di ricerca. |
| ignoreCase | **bool** | Specifica se il confronto è sensibile alle maiuscole. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura da utilizzare durante il confronto di stringhe. |

### Valore restituito

true se la stringa termina con la sottostringa specificata, false altrimenti.

## Vedi anche

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)