---
title: Split()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Dzieli ciąg znaków według znaku.
type: docs
weight: 768
url: /pl/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const metoda

Dzieli ciąg według znaku.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| separator | char_t | Znak, którym dzielony jest ciąg. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opcje dzielenia. |

### Wartość zwracana

[Array](../../array/) podciągów.

## String::Split(char_t, int32_t, StringSplitOptions) const metoda

Dzieli ciąg według znaku.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| separator | char_t | Znak, którym dzielony jest ciąg. |
| count | **int32_t** | Maksymalna liczba podciągów do zwrócenia. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opcje dzielenia. |

### Wartość zwracana

[Array](../../array/) podciągów.

## String::Split(char_t, char_t, StringSplitOptions) const metoda

Dzieli ciąg według jednego z dwóch znaków.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| separatorA | char_t | Pierwszy znak, którym dzielony jest ciąg. |
| separatorB | char_t | Drugi znak, którym dzielony jest ciąg. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opcje dzielenia. |

### Wartość zwracana

[Array](../../array/) podciągów.

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const metoda

Dzieli ciąg według jednego ze wskazanych znaków.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) znaków separatora. Jeśli puste, każdy znak biały jest traktowany jako separator. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opcje dzielenia. |

### Wartość zwracana

[Array](../../array/) podciągów.

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const metoda

Dzieli ciąg według jednego ze wskazanych znaków.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) znaków separatora. Jeśli puste, każdy znak biały jest traktowany jako separator. |
| count | **int32_t** | Maksymalna liczba podciągów do zwrócenia. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opcje dzielenia. |

### Wartość zwracana

[Array](../../array/) podciągów.

## String::Split(const String\&, StringSplitOptions) const metoda

Dzieli ciąg według podciągu.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| separator | const [String](../)\& | Podciąg działający jako separator. Jeśli pusty, znak biały działa jako separator. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opcje dzielenia. |

### Wartość zwracana

[Array](../../array/) podciągów.

## String::Split(const String\&, int, StringSplitOptions) const metoda

Dzieli ciąg według podciągu.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| separator | const [String](../)\& | Podciąg działający jako separator. Jeśli pusty, znak biały działa jako separator. |
| count | int | Maksymalna liczba elementów w tablicy wyników. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opcje dzielenia. |

### Wartość zwracana

[Array](../../array/) podciągów.

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const metoda

Dzieli ciąg według podciągu.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) ciągów separatora. Jeśli puste, nie odbywa się dzielenie. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opcje dzielenia. |

### Wartość zwracana

[Array](../../array/) podciągów.

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const metoda

Dzieli ciąg według podciągu. Obecnie obsługuje tylko tablicę separatorów o zerowej lub jednej elementach.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) ciągów separatora. Jeśli puste, nie odbywa się dzielenie. |
| count | int | Maksymalna liczba elementów w tablicy wyników. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opcje dzielenia. |

### Wartość zwracana

[Array](../../array/) podciągów.

## Zobacz także

* Enum [StringSplitOptions](../../stringsplitoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)