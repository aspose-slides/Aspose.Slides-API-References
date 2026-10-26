---
title: IndexOfAny()
second_title: Aspose.Slides C++ API-referencia
description: Karakter előre keresése.
type: docs
weight: 638
url: /hu/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const method


A karakter előre keresése.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| c | char_t | A keresendő karakter. |
| startIndex | int | [Index](../../index/) a keresés indításához. |

### Visszatérési érték

[Index](../../index/) az első karakter pozíciója a startIndex óta, vagy -1, ha nem található.

## String::IndexOfAny(const String\&, int) const method


Ezután keres minden karaktert a str-ben. Ha az első karakter megtalálható, annak pozíciója kerül visszaadásra, egyébként a második karaktert és így tovább keresi.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) a keresendő karakterek. A karakterek sorrendje számít. |
| startIndex | int | A keresés indítási pozíciója. |

### Visszatérési érték

[Index](../../index/) az első megtalált karakter vagy -1, ha nincs.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const method


Keres bármely átadott karaktert az egész karakterláncban. Az első karaktert összehasonlítja az anyOf összes karakterével, majd a másodikkal stb. Visszaadja az első egyező karakter indexét.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) a keresendő karakterek. A sorrend nem számít. |

### Visszatérési érték

[Index](../../index/) az első egyező karakter vagy -1, ha nem található.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method


Keres bármely átadott karaktert az adott részkarakterláncban. Az első karaktert összehasonlítja az anyOf összes karakterével, majd a másodikkal stb. Visszaadja az első egyező karakter indexét.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) a keresendő karakterek. A sorrend nem számít. |
| startindex | **int32_t** | [Index](../../index/) a keresés indítási pontjának. |

### Visszatérési érték

[Index](../../index/) az első egyező karakter vagy -1, ha nem található.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method


Keres bármely átadott karaktert az adott részkarakterláncban. Az első karaktert összehasonlítja az anyOf összes karakterével, majd a másodikkal stb. Visszaadja az első egyező karakter indexét.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) a keresendő karakterek. A sorrend nem számít. |
| startindex | **int32_t** | [Index](../../index/) a keresés indítási pontjának. |
| count | **int32_t** | A keresendő karakterek száma. |

### Visszatérési érték

[Index](../../index/) az első egyező karakter vagy -1, ha nem található.

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Osztály [String](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)