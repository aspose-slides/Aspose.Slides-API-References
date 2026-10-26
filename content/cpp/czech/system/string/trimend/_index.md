---
title: TrimEnd()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Odstraňuje všechny bílé znaky z konce řetězce.
type: docs
weight: 703
url: /cs/system/string/trimend/
---
## String::TrimEnd() const method

Odstraní všechny bílé znaky z konce řetězce.

```cpp
String System::String::TrimEnd() const
```

### Návratová hodnota

[String](../) s žádnými bílými znaky na začátku.

## String::TrimEnd(char_t) const method

Odstraní všechny výskyty předaného znaku z konce řetězce.

```cpp
String System::String::TrimEnd(char_t ch) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ch | char_t | Symbol k odstranění. |

### Návratová hodnota

Výsledek odstranění.

## String::TrimEnd(const String\&) const method

Odstraní všechny výskyty předaných znaků z konce řetězce.

```cpp
String System::String::TrimEnd(const String &anyOf) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) znaků k odstranění. |

### Návratová hodnota

[String](../) bez odstraněných znaků.

## String::TrimEnd(const ArrayPtr\<char_t\>\&) const method

Odstraní všechny výskyty předaných znaků z konce řetězce.

```cpp
String System::String::TrimEnd(const ArrayPtr<char_t> &anyOf) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) znaků k odstranění. |

### Návratová hodnota

[String](../) bez odstraněných znaků.

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Třída [String](../)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)