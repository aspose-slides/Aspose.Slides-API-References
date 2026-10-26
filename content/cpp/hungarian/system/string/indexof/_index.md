---
title: IndexOf()
second_title: Aspose.Slides for C++ API referenciája
description: Alkarakterlánc előre keresése.
type: docs
weight: 625
url: /hu/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const metódus

Alkarakterlánc előre keresése.

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../)\& | Alkarakterlánc, amelyet keresni kell. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mód. |

### Visszatérési érték

[Index](../../index/) az első megtalált alkarakterlánc indexe, vagy -1, ha nem található. Üres keresési karakterláncnál mindig 0-t ad vissza.

## String::IndexOf(char_t, int) const metódus

Karakter előre keresése.

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| c | char_t | Karakter, amelyet keresni kell. |
| startIndex | int | [Index](../../index/) a keresés kiindulási pontja. |

### Visszatérési érték

[Index](../../index/) az első karakter pozíciója a startIndex-től kezdve, vagy -1, ha nem található.

## String::IndexOf(char_t, int, int) const metódus

Karakter előre keresése alkarakterláncban.

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| c | char_t | Karakter, amelyet keresni kell. |
| startIndex | int | [Index](../../index/) a keresés kiindulási pontja. |
| count | int | A keresendő karakterek száma. |

### Visszatérési érték

[Index](../../index/) az első karakter pozíciója a startIndex-től kezdve, vagy -1, ha nem található.

## String::IndexOf(const String\&, int) const metódus

Alkarakterlánc előre keresése.

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../)\& | Alkarakterlánc, amelyet keresni kell. |
| startIndex | int | Pozíció a forráskarakterláncban, ahol a keresést elindítjuk. |

### Visszatérési érték

[Index](../../index/) az első megtalált alkarakterlánc indexe, vagy -1, ha nem található. Üres keresési karakterláncnál mindig a startIndex-t adja vissza.

## String::IndexOf(const String\&, int, System::StringComparison) const metódus

Alkarakterlánc előre keresése.

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../)\& | Alkarakterlánc, amelyet keresni kell. |
| startIndex | int | Pozíció a forráskarakterláncban, ahol a keresést elindítjuk. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mód. |

### Visszatérési érték

[Index](../../index/) az első megtalált alkarakterlánc indexe, vagy -1, ha nem található. Üres keresési karakterláncnál mindig a startIndex-t adja vissza.

## String::IndexOf(const String\&, int, int, System::StringComparison) const metódus

Alkarakterlánc előre keresése.

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../)\& | Alkarakterlánc, amelyet keresni kell. |
| startIndex | int | Pozíció a forráskarakterláncban, ahol a keresést elindítjuk. |
| count | int | a keresendő karakterek száma. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mód. |

### Visszatérési érték

[Index](../../index/) az első megtalált alkarakterlánc indexe, vagy -1, ha nem található. Üres keresési karakterláncnál mindig a startIndex-t adja vissza.

## String::IndexOf(const String\&, int, int) const metódus

Alkarakterlánc előre keresése.

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../)\& | Alkarakterlánc, amelyet keresni kell. |
| startIndex | int | Pozíció a forráskarakterláncban, ahol a keresést elindítjuk. |
| count | int | a keresendő karakterek száma. |

### Visszatérési érték

[Index](../../index/) az első megtalált alkarakterlánc indexe, vagy -1, ha nem található. Üres keresési karakterláncnál mindig a startIndex-t adja vissza.

## Lásd még

* Enumeráció [StringComparison](../../stringcomparison/)
* Osztály [String](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)