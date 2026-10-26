---
title: WriteAllLines()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen kodlamayı kullanarak yeni bir metin dosyası oluşturur veya mevcut dosyayı üzerine yazar ve belirtilen dize koleksiyonundaki tüm dizeleri dosyaya yazar; her dize yeni bir satıra konur.
type: docs
weight: 456
url: /tr/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) yöntemi


Belirtilen kodlamayı kullanarak, yeni bir metin dosyası oluşturur veya mevcut dosyayı üzerine yazar ve belirtilen dize koleksiyonundaki tüm dizeleri dosyaya yazar; her dize yeni bir satıra konur.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Oluşturulacak veya üzerine yazılacak dosya |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Dizelerden oluşan bir enumerable koleksiyon |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kullanılacak karakter kodlaması |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) yöntemi


Belirtilen kodlamayı kullanarak, yeni bir metin dosyası oluşturur veya mevcut dosyayı üzerine yazar ve belirtilen dize dizisindeki tüm dizeleri dosyaya yazar; her dize yeni bir satıra konur.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Oluşturulacak veya üzerine yazılacak dosya |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Bir dize dizisi |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kullanılacak karakter kodlaması |

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [IEnumerable](../../../system.collections.generic/ienumerable/)
* Sınıf [File](../)
* Ad Alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)