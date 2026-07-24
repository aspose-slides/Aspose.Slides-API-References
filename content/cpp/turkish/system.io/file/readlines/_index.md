---
title: ReadLines()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen metin dosyasının içeriğini, belirtilen karakter kodlamasını kullanarak satır satır okur ve dosyanın içeriğinin tek bir satırını temsil eden dize koleksiyonunu döndürür.
type: docs
weight: 326
url: /tr/system.io/file/readlines/
---
## File::ReadLines(const String\&, const EncodingPtr\&) metod


Belirtilen karakter kodlamasını kullanarak belirli metin dosyasının içeriğini satır satır okur ve her biri dosyanın içeriğinin tek bir satırını temsil eden dize koleksiyonunu döndürür.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Okunacak dosyanın yolu |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kullanılacak karakter kodlaması |

### Dönüş Değeri

Belirtilen dosyanın içeriğini temsil eden dize koleksiyonunun bir yinelemeli koleksiyonu

## Diğer

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)