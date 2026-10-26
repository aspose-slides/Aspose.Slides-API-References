---
title: TrimStart()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort alla blankstegstecken från början av strängen.
type: docs
weight: 690
url: /sv/system/string/trimstart/
---
## String::TrimStart() const metod

Tar bort alla blankstegstecken från början av strängen.

```cpp
String System::String::TrimStart() const
```

### Returvärde

[String](../) utan blanksteg i början.

## String::TrimStart(char_t) const metod

Tar bort alla förekomster av det angivna tecknet från början av strängen.

```cpp
String System::String::TrimStart(char_t ch) const
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| ch | char_t | Symbol att ta bort. |

### Returvärde

Resultatet av borttagning.

## String::TrimStart(const String\&) const metod

Tar bort alla förekomster av de angivna tecknen från början av strängen.

```cpp
String System::String::TrimStart(const String &anyOf) const
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) av tecken att ta bort. |

### Returvärde

[String](../) utan borttagna tecken.

## String::TrimStart(const ArrayPtr\<char_t\>\&) const metod

Tar bort alla förekomster av de angivna tecknen från början av strängen.

```cpp
String System::String::TrimStart(const ArrayPtr<char_t> &anyOf) const
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) av tecken att ta bort. |

### Returvärde

[String](../) utan borttagna tecken.

## Se också

* Typedef [ArrayPtr](../../arrayptr/)
* Klass [String](../)
* Namnrymd [System](../../)
* Library [Aspose.Slides](../../../)