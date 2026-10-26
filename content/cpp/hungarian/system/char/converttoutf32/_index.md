---
title: ConvertToUtf32()
second_title: Aspose.Slides C++ API Referencia
description: Átalakítja a megadott UTF-16 szurrogátpárt UTF-32 kódegységgé.
type: docs
weight: 287
url: /hu/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) metódus


Átalakítja a megadott UTF-16 szurrogátpárt UTF-32 kódegységgé.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| highSurrogate | char_t | A konvertálandó UTF-16 szurrogátpár magas szurrogátja |
| lowSurrogate | char_t | A konvertálandó UTF-16 szurrogátpár alacsony szurrogátja |

### Visszatérési érték

A konverzió eredményeként kapott UTF-32 kódegység

## Char::ConvertToUtf32(const String\&, int) metódus


Átalakítja egy UTF-16 kódolású karakter vagy szurrogátpár egy adott pozícióban lévő értékét egy karakterláncban UTF-32 kódegységgé.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../string/)\& | Egy karakterlánc, amely karaktert vagy szurrogátpárt tartalmaz |
| index | int | A karakter vagy szurrogátpár indexpozíciója a megadott karakterláncban |

### Visszatérési érték

A konverzió eredményeként kapott UTF-32 kódegység

## Lásd még

* Osztály [Char](../)
* Osztály [String](../../string/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)