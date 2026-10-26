---
title: get_Encoding()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací úroveň kódování XML dokumentu.
type: docs
weight: 14
url: /cs/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() metoda

Vrací úroveň kódování XML dokumentu.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```

### Návratová hodnota

Platný název znakové sady.

## Poznámky

Nejčastěji podporované názvy znakových sad pro XML jsou následující:

| Kategorie | Názvy kódování |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (kde "n" je číslice od 1 do 9) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |

Tato hodnota je nepovinná. Pokud hodnota není nastavena, tato metoda vrátí [String::Empty](../../../system/string/empty/). Pokud není zahrnut atribut kódování, předpokládá se kódování UTF-8 při zápisu nebo uložení dokumentu.

## Viz také

* Class [String](../../../system/string/)
* Class [XmlDeclaration](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)