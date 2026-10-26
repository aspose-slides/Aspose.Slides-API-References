---
title: TrimEnd()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort alla blankstegstecken från strängens slut.
type: docs
weight: 703
url: /sv/system/string/trimend/
---
## String::TrimEnd() const metod

Tar bort alla blankstegstecken från strängens slut.

```cpp
String System::String::TrimEnd() const
```

### Returvärde

[String](../) utan mellanslag i början.

## String::TrimEnd(char_t) const metod

Tar bort alla förekomster av det angivna tecknet från strängens slut.

```cpp
String System::String::TrimEnd(char_t ch) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ch | char_t | Symbol att ta bort. |

### Returvärde

Resultat av borttagning.

## String::TrimEnd(const String\&) const metod

Tar bort alla förekomster av de angivna tecknen från strängens slut.

```cpp
String System::String::TrimEnd(const String &anyOf) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) av tecken att ta bort. |

### Returvärde

[String](../) utan borttagna tecken.

## String::TrimEnd(const ArrayPtr\<char_t\>\&) const metod

Tar bort alla förekomster av de angivna tecknen från strängens slut.

```cpp
String System::String::TrimEnd(const ArrayPtr<char_t> &anyOf) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) av tecken att ta bort. |

### Returvärde

[String](../) utan borttagna tecken.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)