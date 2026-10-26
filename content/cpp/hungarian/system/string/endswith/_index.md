---
title: EndsWith()
second_title: Aspose.Slides C++ API hivatkozás
description: Ellenőrzi, hogy a karakterlánc a megadott részsztringgel végződik-e.
type: docs
weight: 482
url: /hu/system/string/endswith/
---
## String::EndsWith(const String\&) const metódus


Ellenőrzi, hogy a karakterlánc a megadott részsztringgel végződik-e.

```cpp
bool System::String::EndsWith(const String &value) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../)\& | Keresett karakterlánc. |

### Visszatérési érték

true ha a karakterlánc a meghatározott részsztringgel végződik, false egyébként.

## String::EndsWith(const String\&, System::StringComparison) const metódus


Ellenőrzi, hogy a karakterlánc a megadott részsztringgel végződik-e.

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../)\& | Keresett karakterlánc. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mód, lásd [System::StringComparison](../../stringcomparison/) a részletekért. |

### Visszatérési érték

true ha a karakterlánc a meghatározott részsztringgel végződik, false egyébként.

## String::EndsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const metódus


Ellenőrzi, hogy a karakterlánc a megadott részsztringgel végződik-e.

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../)\& | Keresett karakterlánc. |
| ignoreCase | **bool** | Megadja, hogy az összehasonlítás kis- és nagybetű érzéketlen-e. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | A karakterlánc-összehasonlítás során használandó kultúra. |

### Visszatérési érték

true ha a karakterlánc a meghatározott részsztringgel végződik, false egyébként.

## Lásd még

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)