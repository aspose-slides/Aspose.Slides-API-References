---
title: Split()
second_title: Aspose.Slides C++ API Referencia
description: A sztringet karakter alapján felosztja.
type: docs
weight: 768
url: /hu/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const metódus


Az karakter alapján felosztja a sztringet.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| separator | char_t | A karakter, amellyel a sztringet felosztják. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Felosztási beállítások. |

### Visszatérési érték

[Array](../../array/) darab részsztring.

## String::Split(char_t, int32_t, StringSplitOptions) const metódus


Az karakter alapján felosztja a sztringet.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| separator | char_t | A karakter, amellyel a sztringet felosztják. |
| count | **int32_t** | A visszaadandó részsztringek maximális száma. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Felosztási beállítások. |

### Visszatérési érték

[Array](../../array/) darab részsztring.

## String::Split(char_t, char_t, StringSplitOptions) const metódus


Az egyik két karakter alapján felosztja a sztringet.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| separatorA | char_t | Az első karakter, amellyel a sztringet felosztják. |
| separatorB | char_t | A második karakter, amellyel a sztringet felosztják. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Felosztási beállítások. |

### Visszatérési érték

[Array](../../array/) darab részsztring.

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const metódus


A megadott karakterek egyikével osztja fel a sztringet.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) a szeparátor karakterek. Ha üres, bármely szóköz karaktert szeparátornak tekintik. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Felosztási beállítások. |

### Visszatérési érték

[Array](../../array/) darab részsztring.

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const metódus


A megadott karakterek egyikével osztja fel a sztringet.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) a szeparátor karakterek. Ha üres, bármely szóköz karaktert szeparátornak tekintik. |
| count | **int32_t** | A visszaadandó részsztringek maximális száma. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Felosztási beállítások. |

### Visszatérési érték

[Array](../../array/) darab részsztring.

## String::Split(const String\&, StringSplitOptions) const metódus


Az altring alapján felosztja a sztringet.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| separator | const [String](../)\& | Az elválasztóként működő altring. Ha üres, a szóköz karakter lesz elválasztó. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Felosztási beállítások. |

### Visszatérési érték

[Array](../../array/) darab részsztring.

## String::Split(const String\&, int, StringSplitOptions) const metódus


Az altring alapján felosztja a sztringet.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| separator | const [String](../)\& | Az elválasztóként működő altring. Ha üres, a szóköz karakter lesz elválasztó. |
| count | int | A felosztott tömb elemeinek maximális száma. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Felosztási beállítások. |

### Visszatérési érték

[Array](../../array/) darab részsztring.

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const metódus


Az altring alapján felosztja a sztringet.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) a szeparátor karakterláncok. Ha üres, nem történik felosztás. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Felosztási beállítások. |

### Visszatérési érték

[Array](../../array/) darab részsztring.

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const metódus


Az altring alapján felosztja a sztringet. Jelenleg csak egy vagy nulla elemből álló elválasztó tömböt támogat.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) a szeparátor karakterláncok. Ha üres, nem történik felosztás. |
| count | int | A felosztott tömb elemeinek maximális száma. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Felosztási beállítások. |

### Visszatérési érték

[Array](../../array/) darab részsztring.

## Lásd még

* Enum [StringSplitOptions](../../stringsplitoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)