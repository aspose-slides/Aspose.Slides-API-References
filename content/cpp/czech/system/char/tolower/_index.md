---
title: ToLower()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Převede zadaný znak na malá písmena.
type: docs
weight: 235
url: /cs/system/char/tolower/
---
## Char::ToLower(char_t) method


Převede zadaný znak na malá písmena.

```cpp
static char_t System::Char::ToLower(char_t c)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| c | char_t | Znak k převodu |

### Návratová hodnota

Zadaný znak v malých písmenech, pokud je zadaný znak velké písmeno, jinak - původní znak

## Char::ToLower(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) method


Převede zadaný znak na malá písmena.

```cpp
static char_t System::Char::ToLower(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| c | char_t | Znak k převodu |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Objekt, který poskytuje pravidla pro změnu velikosti písmen specifická pro kulturu. |

### Návratová hodnota

Zadaný znak v malých písmenech, pokud je zadaný znak velké písmeno, jinak - původní znak

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [Char](../)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)