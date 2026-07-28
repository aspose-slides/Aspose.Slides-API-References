---
title: LastIndexOfAny()
second_title: Aspose.Slides C++ API referencia
description: Megkeresi a megadott karakterek bármelyikét a teljes karakterláncban visszafelé. Összehasonlítja az utolsó karaktert az anyOf összes karakterével, majd az előzőt és így tovább. Visszaadja az első megtalált egyezés indexét.
type: docs
weight: 664
url: /hu/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const metódus

Megkeresi a megadott karakterek bármelyikét a teljes karakterláncban visszafelé. Összehasonlítja az utolsó karaktert az anyOf összes karakterével, majd az előzőt és így tovább. Visszaadja az első megtalált egyezés indexét.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) a keresendő karakterek. A sorrend nem számít. |

### Visszatérési érték

[Index](../../index/) az utolsó egyező karakter indexe vagy -1, ha nem található.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const metódus

Megkeresi a megadott karakterek bármelyikét a részkarakterláncban visszafelé. Összehasonlítja az utolsó karaktert az anyOf összes karakterével, majd az előzőt és így tovább. Visszaadja az első megtalált egyezés indexét.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) a keresendő karakterek. A sorrend nem számít. |
| startindex | **int32_t** | [Index](../../index/) a keresés kezdési indexe. |

### Visszatérési érték

[Index](../../index/) az utolsó egyező karakter indexe vagy -1, ha nem található.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const metódus

Megkeresi a megadott karakterek bármelyikét a részkarakterláncban visszafelé. Összehasonlítja az utolsó karaktert az anyOf összes karakterével, majd az előzőt és így tovább. Visszaadja az első megtalált egyezés indexét.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) a keresendő karakterek. A sorrend nem számít. |
| startindex | **int32_t** | [Index](../../index/) a keresés kezdési indexe. |
| count | **int32_t** | A keresendő karakterek száma. |

### Visszatérési érték

[Index](../../index/) az utolsó egyező karakter indexe vagy -1, ha nem található.

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Osztály [String](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)