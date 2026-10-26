---
title: Trim()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort alla blankstegstecken från både början och slutet av strängen.
type: docs
weight: 677
url: /sv/system/string/trim/
---
## String::Trim() const metod

Tar bort alla blankstegstecken från både början och slutet av strängen.

```cpp
String System::String::Trim() const
```

### Returvärde

[String](../) utan blanksteg i början eller slutet.

## String::Trim(char_t) const metod

Tar bort alla förekomster av det angivna tecknet från både början och slutet av strängen.

```cpp
String System::String::Trim(char_t ch) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ch | char_t | Symbol att ta bort. |

### Returvärde

Resultat av borttagning.

## String::Trim(const String\&) const metod

Tar bort alla förekomster av de angivna tecknen från både början och slutet av strängen.

```cpp
String System::String::Trim(const String &anyOf) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) av tecken att ta bort. |

### Returvärde

[String](../) utan borttagna tecken.

## String::Trim(const ArrayPtr\<char_t\>\&) const metod

Tar bort alla förekomster av de angivna tecknen från både början och slutet av strängen.

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) av tecken att ta bort. |

### Returvärde

[String](../) utan borttagna tecken.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Klass [String](../)
* Namnrymd [System](../../)
* Library [Aspose.Slides](../../../)