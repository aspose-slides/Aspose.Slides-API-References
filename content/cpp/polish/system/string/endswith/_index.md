---
title: EndsWith()
second_title: Aspose.Slides dla C++ Referencja API
description: Sprawdza, czy ciąg kończy się określonym podciągiem.
type: docs
weight: 482
url: /pl/system/string/endswith/
---
## String::EndsWith(const String\&) const metoda


Sprawdza, czy ciąg kończy się podanym podciągiem.

```cpp
bool System::String::EndsWith(const String &value) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../)\& | Ciąg do wyszukania. |

### Wartość zwracana

true, jeśli ciąg kończy się podanym podciągiem, false w przeciwnym razie.

## String::EndsWith(const String\&, System::StringComparison) const metoda


Sprawdza, czy ciąg kończy się podanym podciągiem.

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../)\& | Ciąg do wyszukania. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) tryb, zobacz [System::StringComparison](../../stringcomparison/) po szczegóły. |

### Wartość zwracana

true, jeśli ciąg kończy się podanym podciągiem, false w przeciwnym razie.

## String::EndsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const metoda


Sprawdza, czy ciąg kończy się podanym podciągiem.

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../)\& | Ciąg do wyszukania. |
| ignoreCase | **bool** | Określa, czy porównanie jest wielko-literowo niewrażliwe. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura używana podczas wykonywania porównania ciągów. |

### Wartość zwracana

true, jeśli ciąg kończy się podanym podciągiem, false w przeciwnym razie.

## Zobacz także

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasa [String](../)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)