---
title: get_Encoding()
second_title: Aspose.Slides dla C++ – referencja API
description: Zwraca poziom kodowania dokumentu XML.
type: docs
weight: 14
url: /pl/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() metoda

Zwraca poziom kodowania dokumentu XML.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```

### Wartość zwracana

Poprawna nazwa kodowania znaków.

## Uwagi

Najczęściej obsługiwane nazwy kodowań znaków dla XML są następujące:

| Kategoria | Nazwy kodowań |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (gdzie "n" jest cyfrą od 1 do 9) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |

Ta wartość jest opcjonalna. Jeśli wartość nie jest ustawiona, ta metoda zwraca [String::Empty](../../../system/string/empty/). Jeśli atrybut kodowania nie jest zawarty, przy zapisie lub zapisywaniu dokumentu przyjmowane jest kodowanie UTF-8.

## Zobacz też

* 
* Klasa [String](../../../system/string/)
* Klasa [XmlDeclaration](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)