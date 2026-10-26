---
title: ToUpper()
second_title: Aspose.Slides C++ API Referencia
description: Átalakítja a megadott karaktert nagybetűvé.
type: docs
weight: 222
url: /hu/system/char/toupper/
---
## Char::ToUpper(char_t) metódus

Átalakítja a megadott karaktert nagybetűvé.

```cpp
static char_t System::Char::ToUpper(char_t c)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| c | char_t | A konvertálandó karakter |

### Visszatérési érték

A megadott karakter nagybetűs változata, ha a megadott karakter kisbetű, egyébként – a megadott karakter

## Char::ToUpper(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) metódus

Átalakítja a megadott karaktert nagybetűvé.

```cpp
static char_t System::Char::ToUpper(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| c | char_t | A konvertálandó karakter |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Egy objektum, amely kultúraspecifikus nagybetű-kisbetű szabályokat biztosít. |

### Visszatérési érték

A megadott karakter nagybetűs változata, ha a megadott karakter kisbetű, egyébként – a megadott karakter

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [Char](../)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)