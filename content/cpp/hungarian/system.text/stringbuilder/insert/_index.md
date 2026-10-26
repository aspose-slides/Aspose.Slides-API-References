---
title: Insert()
second_title: Aspose.Slides C++ API referencia
description: Beszúrja a karakterláncot a builder rögzített pozíciójába.
type: docs
weight: 183
url: /hu/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) metódus


Beszúrja a karakterláncot a builder rögzített pozíciójába.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | int | A karakterek beszúrásának pozíciója. |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) beszúrandó. |

### Visszatérési érték

Ez a pointer.

## StringBuilder::Insert(int32_t, const String\&, int32_t) metódus


Ismételt karakterláncot szúr be a builder rögzített pozíciójába.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A karakterek beszúrásának pozíciója. |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) beszúrandó. |
| count | **int32_t** | Hányszor kell ismételni a **value** karakterláncot. |

### Visszatérési érték

Ez a pointer.

## StringBuilder::Insert(int, char_t) metódus


Karaktert szúr be a builder rögzített pozíciójába.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | int | A karakterek beszúrásának pozíciója. |
| ch | char_t | Beszúrandó karakter. |

### Visszatérési érték

Ez a pointer.

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) metódus


Karaktereket szúr be a builder rögzített pozíciójába.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A karakterek beszúrásának pozíciója. |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) szeletből beszúrandó. |
| startIndex | int | [Array](../../../system/array/) szelet kezdőindexe. |
| charCount | int | [Array](../../../system/array/) szelet hossza. |

### Visszatérési érték

Ez a pointer.

## StringBuilder::Insert(int, T) metódus


Értéket szúr be a builder rögzített pozíciójába.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Parameter | típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | int | A karakterek beszúrásának pozíciója. |
| value | T | Formázandó és beszúrandó érték. |

### Visszatérési érték

Ez a pointer.

## Lásd még

* Osztály [ArrayPtr](../../../system/arrayptr/)
* Osztály [StringBuilder](../)
* Osztály [String](../../../system/string/)
* Névterület [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)