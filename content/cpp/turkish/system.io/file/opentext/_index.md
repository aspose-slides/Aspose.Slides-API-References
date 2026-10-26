---
title: OpenText()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen mevcut dosyayı, paylaşımsız UTF-8 kodlaması kullanarak metin okumak için açar.
type: docs
weight: 261
url: /tr/system.io/file/opentext/
---
## File::OpenText(const String\&, const EncodingPtr\&) metodu

Belirtilen mevcut dosyayı, paylaşımsız UTF-8 kodlaması kullanarak metin okumak için açar.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Açılacak dosyanın yolu |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kullanılacak karakter kodlaması |

### Dönüş Değeri

Açılan dosyayla ilişkili bir [StreamWriter](../../streamwriter/) nesnesine paylaşımlı işaretçi

## İlgili

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [File](../)
* Ad alanı [System::IO](../../)
* Library [Aspose.Slides](../../../)