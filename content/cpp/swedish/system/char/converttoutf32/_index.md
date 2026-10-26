---
title: ConvertToUtf32()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar det angivna UTF-16-surrogatparet till en UTF-32-kod enhet.
type: docs
weight: 287
url: /sv/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) metod


Konverterar den angivna UTF-16-surrogatparet till en UTF-32-kod enhet.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| highSurrogate | char_t | Den höga surrogaten för UTF-16-surrogatparet som ska konverteras |
| lowSurrogate | char_t | Den låga surrogaten för UTF-16-surrogatparet som ska konverteras |

### Return Value

En UTF-32-kod enhet som resultat av konverteringen

## Char::ConvertToUtf32(const String\&, int) metod


Konverterar värdet av ett UTF-16-kodat tecken eller surrogatpar på en angiven position i en sträng till en UTF-32-kod enhet.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../string/)\& | En sträng som innehåller ett tecken eller surrogatpar |
| index | int | Indexpositionen för tecknet eller surrogatparet i den angivna strängen |

### Return Value

En UTF-32-kod enhet som resultat av konverteringen

## Se även

* Klass [Char](../)
* Klass [String](../../string/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)