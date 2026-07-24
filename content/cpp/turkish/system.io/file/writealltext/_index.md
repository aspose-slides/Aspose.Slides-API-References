---
title: WriteAllText()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen kodlamayı kullanarak, belirtilen dizenin içeriğini dosyaya yazar ve yeni bir metin dosyası oluşturur ya da mevcut dosyanın üzerine yazar.
type: docs
weight: 469
url: /tr/system.io/file/writealltext/
---
## File::WriteAllText(const String\&, const String\&, const EncodingPtr\&) metodu

Belirtilen String'in içeriğini, belirtilen kodlamayı kullanarak dosyaya yazar ve yeni bir metin dosyası oluşturur veya mevcut dosyanın üzerine yazar.

```cpp
static void System::IO::File::WriteAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Oluşturulacak veya üzerine yazılacak dosya |
| contents | const [String](../../../system/string/)\& | Dize dizisi |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kullanılacak karakter kodlaması |

## İlgili

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)