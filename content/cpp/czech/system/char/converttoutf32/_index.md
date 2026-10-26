---
title: ConvertToUtf32()
second_title: Aspose.Slides pro C++ API Reference
description: Převádí zadaný pár náhradníků UTF-16 na kódovou jednotku UTF-32.
type: docs
weight: 287
url: /cs/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) metoda


Převádí zadaný pár náhradníků UTF-16 na kódovou jednotku UTF-32.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| highSurrogate | char_t | Vysoký náhradník páru náhradníků UTF-16 k převodu |
| lowSurrogate | char_t | Nízký náhradník páru náhradníků UTF-16 k převodu |

### Návratová hodnota

Kódová jednotka UTF-32 vzniklá převodem

## Char::ConvertToUtf32(const String\&, int) metoda


Převádí hodnotu znaku kódovaného v UTF-16 nebo páru náhradníků na určené pozici v řetězci na kódovou jednotku UTF-32.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Řetězec, který obsahuje znak nebo pár náhradníků |
| index | int | Indexová pozice znaku nebo páru náhradníků ve zadaném řetězci |

### Návratová hodnota

Kódová jednotka UTF-32 vzniklá převodem

## Další informace

* Třída [Char](../)
* Třída [String](../../string/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)