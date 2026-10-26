---
title: Trim()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Odstraňuje všechny bílé znaky z počátku i konce řetězce.
type: docs
weight: 677
url: /cs/system/string/trim/
---
## String::Trim() const metoda

Odstraní všechny bílé znaky na začátku i na konci řetězce.

```cpp
String System::String::Trim() const
```

### Návratová hodnota

[String](../) bez bílých znaků na začátku ani na konci.

## String::Trim(char_t) const metoda

Odstraní všechny výskyty předaného znaku na začátku i na konci řetězce.

```cpp
String System::String::Trim(char_t ch) const
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| ch | char_t | Symbol k odstranění. |

### Návratová hodnota

Výsledek odstranění.

## String::Trim(const String\&) const metoda

Odstraní všechny výskyty předaných znaků na začátku i na konci řetězce.

```cpp
String System::String::Trim(const String &anyOf) const
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) znaků k odstranění. |

### Návratová hodnota

[String](../) bez odstraněných znaků.

## String::Trim(const ArrayPtr\<char_t\>\&) const metoda

Odstraní všechny výskyty předaných znaků na začátku i na konci řetězce.

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) znaků k odstranění. |

### Návratová hodnota

[String](../) bez odstraněných znaků.

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Třída [String](../)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)