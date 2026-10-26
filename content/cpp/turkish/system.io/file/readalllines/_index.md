---
title: ReadAllLines()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen metin dosyasının içeriğini, belirtilen karakter kodlamasını kullanarak satır satır bir dize dizisine okur.
type: docs
weight: 300
url: /tr/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) metodu

Belirtilen metin dosyasının içeriğini, belirtilen karakter kodlamasını kullanarak satır satır bir dize dizisine okur.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Okunacak dosyanın yolu |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kullanılacak karakter kodlaması |

### Dönüş Değeri

Belirtilen dosyanın her bir satırını temsil eden bir dize dizisi

## Bakınız

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Tip Tanımı [EncodingPtr](../../../system/encodingptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [File](../)
* Ad Alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)