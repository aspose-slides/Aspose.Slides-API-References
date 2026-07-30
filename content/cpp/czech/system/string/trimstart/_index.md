---
title: TrimStart()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Odstraňuje všechny znaky bílého prostoru ze začátku řetězce.
type: docs
weight: 690
url: /cs/system/string/trimstart/
---
## String::TrimStart() const metoda

Odstraní všechny znaky bílého prostoru ze začátku řetězce.

```cpp
String System::String::TrimStart() const
```

### Návratová hodnota

[String](../) bez bílých znaků na začátku.

## String::TrimStart(char_t) const metoda

Odstraní všechny výskyty předaného znaku ze začátku řetězce.

```cpp
String System::String::TrimStart(char_t ch) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ch | char_t | Symbol k odstranění. |

### Návratová hodnota

Výsledek odstranění.

## String::TrimStart(const String\&) const metoda

Odstraní všechny výskyty předaných znaků ze začátku řetězce.

```cpp
String System::String::TrimStart(const String &anyOf) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) znaků k odstranění. |

### Návratová hodnota

[String](../) bez odstraněných znaků.

## String::TrimStart(const ArrayPtr\<char_t\>\&) const metoda

Odstraní všechny výskyty předaných znaků ze začátku řetězce.

```cpp
String System::String::TrimStart(const ArrayPtr<char_t> &anyOf) const
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
* Knihovna [Aspose.Slides](../../../)