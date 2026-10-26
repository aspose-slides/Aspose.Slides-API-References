---
title: Append()
second_title: Aspose.Slides C++ API hivatkozása
description: Karaktert ad a builderhez.
type: docs
weight: 118
url: /hu/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) metódus

Karaktert ad a builderhez.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| c | char_t | Karakter érték. |

### Visszatérési érték

Ez a mutató.

## StringBuilder::Append(char_t, int) metódus

Karaktereket ad a builderhez.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| c | char_t | Karakter érték. |
| count | int | Hányszor kell megismételni a beszúrandó karaktert. |

### Visszatérési érték

Ez a mutató.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) metódus

Karaktertömböt ad a builderhez.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Hozzáadandó karakterek. |

### Visszatérési érték

Ez a mutató.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) metódus

Karaktertömb szeletet ad a builderhez.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Hozzáadandó karakterek. |
| startIndex | int | Szelet kezdő indexe. |
| charCount | int | Szelet hossza. |

### Visszatérési érték

Ez a mutató.

## StringBuilder::Append(const String\&) metódus

Szöveget ad a builderhez.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) hozzáadáshoz. |

### Visszatérési érték

Ez a mutató.

## StringBuilder::Append(const String\&, int, int) metódus

Szöveg szeletet ad a builderhez.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) hozzáadáshoz. |
| startIndex | int | Szelet kezdő indexe. |
| charCount | int | Szelet hossza. |

### Visszatérési érték

Ez a mutató.

## StringBuilder::Append(const SharedPtr\<T\>\&) metódus

Objektum string reprezentációját ad a builderhez.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) sorosításához és hozzáadáshoz. |

### Visszatérési érték

Ez a mutató.

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) metódus

Builder tartalmát adja a builderhez.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | A builder, amelynek a tartalmát hozzáadja. |

### Visszatérési érték

Ez a mutató.

## StringBuilder::Append(float) metódus

Lebegőpontos értéket ad a builderhez.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| f | **float** | Az érték sorosításához és hozzáadáshoz. |

### Visszatérési érték

Ez a mutató.

## StringBuilder::Append(double) metódus

Lebegőpontos értéket ad a builderhez.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| df | **double** | Az érték sorosításához és hozzáadáshoz. |

### Visszatérési érték

Ez a mutató.

## StringBuilder::Append(int) metódus

Egész számot ad a builderhez.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| i | int | Az érték sorosításához és hozzáadáshoz. |

### Visszatérési érték

Ez a mutató.

## StringBuilder::Append(T) metódus

Aritmetikai értéket ad a builderhez.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Aritmetikai típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | T | Az érték sorosításához és hozzáadáshoz. |

### Visszatérési érték

Ez a mutató.

## StringBuilder::Append(E) metódus

Enums érték string reprezentációját ad a builderhez.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| E | [Enum](../../../system/enum/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| e | E | Az érték sorosításához és hozzáadáshoz. |

### Visszatérési érték

Ez a mutató.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)