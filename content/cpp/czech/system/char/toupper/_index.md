---
title: ToUpper()
second_title: Aspose.Slides pro referenci API C++
description: Převede zadaný znak na velké písmeno.
type: docs
weight: 222
url: /cs/system/char/toupper/
---
## Char::ToUpper(char_t) metoda

Převede zadaný znak na velké písmeno.

```cpp
static char_t System::Char::ToUpper(char_t c)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| c | char_t | Znak k převedení |

### Návratová hodnota

Zadaný znak ve velkém písmenu, pokud je zadaný znak malým písmenem, jinak – zadaný znak

## Char::ToUpper(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) metoda

Převede zadaný znak na velké písmeno.

```cpp
static char_t System::Char::ToUpper(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| c | char_t | Znak k převedení |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Objekt, který poskytuje pravidla pro velikost písmen podle konkrétní kultury. |

### Návratová hodnota

Zadaný znak ve velkém písmenu, pokud je zadaný znak malým písmenem, jinak – zadaný znak

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [Char](../)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)