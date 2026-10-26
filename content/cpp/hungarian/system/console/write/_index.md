---
title: Write()
second_title: Aspose.Slides for C++ API referencia
description: A megadott objektum karakterlánc ábrázolását írja ki a szabványos kimeneti folyamra.
type: docs
weight: 1
url: /hu/system/console/write/
---
## Console::Write(const SharedPtr\<T\>\&) metódus

A megadott objektum karakterlánc ábrázolását írja ki a szabványos kimeneti folyamra.

```cpp
template<class T> static void System::Console::Write(const SharedPtr<T> &object)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A kimenetre írandó objektum típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) a kimenetre írásra |

## Console::Write(bool) metódus

A bool érték karakterlánc ábrázolását írja ki a szabványos kimeneti folyamra.

```cpp
static void System::Console::Write(bool value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **bool** | A kimenetre írandó érték |

## Console::Write(char_t) metódus

A megadott karakterérték kimeneti ábrázolását írja ki a szabványos kimeneti folyamra.

```cpp
static void System::Console::Write(char_t value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char_t | A kimenetre írandó érték |

## Console::Write(const ArrayPtr\<char_t\>\&) metódus

A megadott karaktertömb karakterlánc ábrázolását írja ki a szabványos kimeneti folyamra.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | A kimenetre írandó tömb |

## Console::Write(const Decimal\&) metódus

A [Decimal](../../decimal/) érték karakterlánc ábrázolását írja ki a szabványos kimeneti folyamra.

```cpp
static void System::Console::Write(const Decimal &value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | A kimenetre írandó érték |

## Console::Write(double) metódus

A dupla pontosságú lebegőpontos érték karakterlánc ábrázolását írja ki a szabványos kimeneti folyamra.

```cpp
static void System::Console::Write(double value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **double** | A kimenetre írandó érték |

## Console::Write(float) metódus

Az egyszeres pontosságú lebegőpontos érték karakterlánc ábrázolását írja ki a szabványos kimeneti folyamra.

```cpp
static void System::Console::Write(float value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **float** | A kimenetre írandó érték |

## Console::Write(int32_t) metódus

A 32 bites egész szám karakterlánc ábrázolását írja ki a szabványos kimeneti folyamra.

```cpp
static void System::Console::Write(int32_t value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **int32_t** | A kimenetre írandó érték |

## Console::Write(int64_t) metódus

A 64 bites egész szám karakterlánc ábrázolását írja ki a szabványos kimeneti folyamra.

```cpp
static void System::Console::Write(int64_t value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **int64_t** | A kimenetre írandó érték |

## Console::Write(const String\&) metódus

A megadott string objektumot írja ki a szabványos kimeneti folyamra.

```cpp
static void System::Console::Write(const String &value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A kimenetre írandó string objektum |

## Console::Write(const char_t *) metódus

A megadott C-sztringet írja ki a szabványos kimeneti folyamra.

```cpp
static void System::Console::Write(const char_t *value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const char_t * | A kimenetre írandó C-sztring |

## Console::Write(const TypeInfo\&) metódus

A [TypeInfo](../../typeinfo/) érték karakterlánc ábrázolását írja ki a szabványos kimeneti folyamra.

```cpp
static void System::Console::Write(const TypeInfo &value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | A kimenetre írandó érték |

## Console::Write(uint32_t) metódus

A 32 bites előjeles nélküli egész szám karakterlánc ábrázolását írja ki a szabványos kimeneti folyamra.

```cpp
static void System::Console::Write(uint32_t value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **uint32_t** | A kimenetre írandó érték |

## Console::Write(uint64_t) metódus

A 64 bites előjeles nélküli egész szám karakterlánc ábrázolását írja ki a szabványos kimeneti folyamra.

```cpp
static void System::Console::Write(uint64_t value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **uint64_t** | A kimenetre írandó érték |

## Console::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metódus

A megadott karaktertömb megadott tartományának karakterlánc ábrázolását írja ki a szabványos kimeneti folyamra.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | A karaktertömb |
| index | **int32_t** | Az index a tömbben, ahol a kimenetre írandó tartomány kezdődik |
| count | **int32_t** | A kimenetre írandó tartomány elemeinek száma |

## Console::Write(const String\&, Args\&&...) metódus

A megadott argumentumok a megadott formátum szerint formázott karakterlánc ábrázolását írja ki a szabványos kimeneti folyamra.

```cpp
template<class...> static void System::Console::Write(const String &format, Args &&... args)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| The | a kimenetre írandó értékek típusai |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | const [String](../../string/)\& | A karakterlánc formátuma |
| args | Args\&&... | A kimenetre írandó értékek |

## Console::Write(const char *) metódus


```cpp
static void System::Console::Write(const char *)=delete
```

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [Console](../)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [TypeInfo](../../typeinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)