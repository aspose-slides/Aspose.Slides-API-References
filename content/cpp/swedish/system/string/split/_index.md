---
title: Split()
second_title: Aspose.Slides för C++ API-referens
description: Delar strängen efter ett tecken.
type: docs
weight: 768
url: /sv/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const method

Delar strängen efter ett tecken.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separator | char_t | Tecken att dela strängen efter. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Delningsalternativ. |

### Returvärde

[Array](../../array/) av delsträngar.

## String::Split(char_t, int32_t, StringSplitOptions) const method

Delar strängen efter ett tecken.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separator | char_t | Tecken att dela strängen efter. |
| count | **int32_t** | Det maximala antalet delsträngar att returnera. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Delningsalternativ. |

### Returvärde

[Array](../../array/) av delsträngar.

## String::Split(char_t, char_t, StringSplitOptions) const method

Delar strängen efter ett av två tecken.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separatorA | char_t | Första tecknet att dela strängen efter. |
| separatorB | char_t | Andra tecknet att dela strängen efter. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Delningsalternativ. |

### Returvärde

[Array](../../array/) av delsträngar.

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const method

Delar strängen efter ett av de angivna tecknen.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) av separatortecken. Om den är tom betraktas varje blankstegstecken som en separator. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Delningsalternativ. |

### Returvärde

[Array](../../array/) av delsträngar.

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const method

Delar strängen efter ett av de angivna tecknen.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) av separatortecken. Om den är tom betraktas varje blankstegstecken som en separator. |
| count | **int32_t** | Det maximala antalet delsträngar att returnera. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Delningsalternativ. |

### Returvärde

[Array](../../array/) av delsträngar.

## String::Split(const String\&, StringSplitOptions) const method

Delar strängen efter en delsträng.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separator | const [String](../)\& | Delsträng som fungerar som separator. Om den är tom fungerar blankstegstecken som separator. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Delningsalternativ. |

### Returvärde

[Array](../../array/) av delsträngar.

## String::Split(const String\&, int, StringSplitOptions) const method

Delar strängen efter en delsträng.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separator | const [String](../)\& | Delsträng som fungerar som separator. Om den är tom fungerar blankstegstecken som separator. |
| count | int | Maximalt antal element i delningsarrayen. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Delningsalternativ. |

### Returvärde

[Array](../../array/) av delsträngar.

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const method

Delar strängen efter en delsträng.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) av separatorsträngar. Om den är tom sker ingen delning. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Delningsalternativ. |

### Returvärde

[Array](../../array/) av delsträngar.

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const method

Delar strängen efter en delsträng. För närvarande stöds bara separatorarray med noll eller ett element.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) av separatorsträngar. Om den är tom sker ingen delning. |
| count | int | Maximalt antal element i delningsarrayen. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Delningsalternativ. |

### Returvärde

[Array](../../array/) av delsträngar.

## Se även

* Enum [StringSplitOptions](../../stringsplitoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)