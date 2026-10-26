---
title: LastIndexOf()
second_title: Aspose.Slides C++ API hivatkozás
description: Alkarakterlánc visszafelé keresése.
type: docs
weight: 651
url: /hu/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const metódus

Alkarakterlánc visszafelé keresése.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Keresendő alkarakterlánc. |
| startIndex | int | A forráskarakterláncban a keresés kezdőpozíciója. |

### Visszatérési érték

[Index](../../index/) az utoljára megtalált alkarakterlánc indexe, vagy -1, ha nem található. Üres keresési karakterláncnál mindig a karakterlánc hossza kerül visszaadásra.

## String::LastIndexOf(const String\&, System::StringComparison) const metódus

Alkarakterlánc visszafelé keresése.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Keresendő alkarakterlánc. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mód. |

### Visszatérési érték

[Index](../../index/) az utoljára megtalált alkarakterlánc indexe, vagy -1, ha nem található. Üres keresési karakterláncnál mindig a karakterlánc hossza kerül visszaadásra.

## String::LastIndexOf(const String\&, int, System::StringComparison) const metódus

Alkarakterlánc visszafelé keresése.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Keresendő alkarakterlánc. |
| startIndex | int | A forráskarakterláncban a keresés kezdőpozíciója. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mód. |

### Visszatérési érték

[Index](../../index/) az utoljára megtalált alkarakterlánc indexe, vagy -1, ha nem található. Üres keresési karakterláncnál mindig a karakterlánc hossza kerül visszaadásra.

## String::LastIndexOf(const String\&, int, int, StringComparison) const metódus

Alkarakterlánc visszafelé keresése.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Keresendő alkarakterlánc. |
| startIndex | int | A forráskarakterláncban a keresés kezdőpozíciója. |
| count | int | Átnézendő karakterek száma. |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mód. |

### Visszatérési érték

[Index](../../index/) az utoljára megtalált alkarakterlánc indexe, vagy -1, ha nem található. Üres keresési karakterláncnál mindig a startIndex+count értéke kerül visszaadásra.

## String::LastIndexOf(char_t) const metódus

Karakter visszafelé keresése.

```cpp
int System::String::LastIndexOf(char_t value) const
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | Keresendő karakter. |

### Visszatérési érték

[Index](../../index/) az utolsó karakter pozíciója, vagy -1, ha nem található.

## String::LastIndexOf(char_t, int32_t) const metódus

Karakter visszafelé keresése.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | Keresendő karakter. |
| startIndex | **int32_t** | [Index](../../index/) a keresés kezdőpozíciója. |

### Visszatérési érték

[Index](../../index/) az utolsó karakter pozíciója a startIndex óta, vagy -1, ha nem található.

## String::LastIndexOf(char_t, int32_t, int32_t) const metódus

Karakter visszafelé keresése.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | Keresendő karakter. |
| startIndex | **int32_t** | [Index](../../index/) a keresés kezdőpozíciója. |
| count | **int32_t** | Átnézendő karakterek száma |

### Visszatérési érték

[Index](../../index/) az utolsó karakter pozíciója a startIndex óta, vagy -1, ha nem található.

## Lásd még

* Enum [StringComparison](../../stringcomparison/)
* Osztály [String](../)
* Névtere [System](../../)
* Könyvtár [Aspose.Slides](../../../)