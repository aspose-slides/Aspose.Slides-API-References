---
title: Split()
second_title: Aspose.Slides voor C++ API-referentie
description: Splitst string op teken.
type: docs
weight: 768
url: /nl/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const method

Splitst string op teken.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separator | char_t | Teken waarop de string wordt gesplitst. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Splitsopties. |

### Returnwaarde

[Array](../../array/) van substrings.

## String::Split(char_t, int32_t, StringSplitOptions) const method

Splitst string op teken.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separator | char_t | Teken waarop de string wordt gesplitst. |
| count | **int32_t** | Het maximale aantal substrings dat wordt geretourneerd. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Splitsopties. |

### Returnwaarde

[Array](../../array/) van substrings.

## String::Split(char_t, char_t, StringSplitOptions) const method

Splitst string op een van twee tekens.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separatorA | char_t | Eerste teken waarop de string wordt gesplitst. |
| separatorB | char_t | Tweede teken waarop de string wordt gesplitst. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Splitsopties. |

### Returnwaarde

[Array](../../array/) van substrings.

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const method

Splitst string op een van de opgegeven tekens.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) van scheidingstekenkarakters. Indien leeg, wordt elk witruimtekarakter beschouwd als scheidingsteken. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Splitsopties. |

### Returnwaarde

[Array](../../array/) van substrings.

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const method

Splitst string op een van de opgegeven tekens.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) van scheidingstekenkarakters. Indien leeg, wordt elk witruimtekarakter beschouwd als scheidingsteken. |
| count | **int32_t** | Het maximale aantal substrings dat wordt geretourneerd. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Splitsopties. |

### Returnwaarde

[Array](../../array/) van substrings.

## String::Split(const String\&, StringSplitOptions) const method

Splitst string op substring.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separator | const [String](../)\& | Substring die dient als scheidingsteken. Indien leeg, dient een witruimtekarakter als scheidingsteken. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Splitsopties. |

### Returnwaarde

[Array](../../array/) van substrings.

## String::Split(const String\&, int, StringSplitOptions) const method

Splitst string op substring.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separator | const [String](../)\& | Substring die dient als scheidingsteken. Indien leeg, dient een witruimtekarakter als scheidingsteken. |
| count | int | Max aantal elementen in splits-array. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Splitsopties. |

### Returnwaarde

[Array](../../array/) van substrings.

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const method

Splitst string op substring.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) van scheidingsteken-strings. Indien leeg, wordt er niet gesplitst. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Splitsopties. |

### Returnwaarde

[Array](../../array/) van substrings.

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const method

Splitst string op substring. Momenteel ondersteunt het alleen een scheidingstekenarray van nul of één elementen.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) van scheidingsteken-strings. Indien leeg, wordt er niet gesplitst. |
| count | int | Max aantal elementen in splits-array. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Splitsopties. |

### Returnwaarde

[Array](../../array/) van substrings.

## Zie ook

* Enum [StringSplitOptions](../../stringsplitoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)