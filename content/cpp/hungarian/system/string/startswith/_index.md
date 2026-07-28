---
title: StartsWith()
second_title: Aspose.Slides C++ API referencia
description: Ellenőrzi, hogy a karakterlánc a megadott részkarakterlánccal kezdődik-e.
type: docs
weight: 469
url: /hu/system/string/startswith/
---
## String::StartsWith(const String\&) const method


Ellenőrzi, hogy a karakterlánc a megadott részkarakterlánccal kezdődik-e.

```cpp
bool System::String::StartsWith(const String &value) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Keresett karakterlánc. |

### Return Value

true if string starts with specified substring, false otherwise.

## String::StartsWith(const String\&, System::StringComparison) const method


Ellenőrzi, hogy a karakterlánc a megadott részkarakterlánccal kezdődik-e.

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Keresett karakterlánc. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mód, lásd [System::StringComparison](../../stringcomparison/) a részletekért. |

### Return Value

true if string starts with specified substring, false otherwise.

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const method


Ellenőrzi, hogy a karakterlánc a megadott részkarakterlánccal kezdődik-e.

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Keresett karakterlánc. |
| ignoreCase | **bool** | Megadja, hogy az összehasonlítás ne vegye figyelembe a kis- és nagybetűket. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | A karakterlánc-összehasonlítás során használandó kultúra. |

### Return Value

true if string starts with specified substring, false otherwise.

## See Also

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)