---
title: ReadAllText()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen karakter kodlamasını kullanarak belirtilen metin dosyasının içeriğini tek bir String nesnesine okur.
type: docs
weight: 313
url: /tr/system.io/file/readalltext/
---
## File::ReadAllText(const String\&, const EncodingPtr\&) yöntemi

Belirtilen metin dosyasının içeriğini, belirtilen karakter kodlamasını kullanarak tek bir [String](../../../system/string/) nesnesine okur.

```cpp
static String System::IO::File::ReadAllText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Okunacak dosyanın yolu |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kullanılacak karakter kodlaması |

### Dönüş Değeri

Belirtilen dosyanın içeriğini içeren bir dize

## Ayrıca Bakınız

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [File](../)
* Ad Alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)