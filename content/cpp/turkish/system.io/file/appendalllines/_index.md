---
title: AppendAllLines()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen kodlamayı kullanarak, belirtilen dize koleksiyonundaki dizeleri, her birini yeni bir satıra yazarak belirtilen dosyaya ekler. Belirtilen dosya mevcut değilse, oluşturulur. Tüm dizeler yazıldıktan sonra dosya kapatılır.
type: docs
weight: 1
url: /tr/system.io/file/appendalllines/
---
## File::AppendAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) metot

Belirtilen kodlama kullanılarak, belirtilen koleksiyondaki dizeleri belirtilen dosyaya, her dizenin yeni bir satıra yazılmasıyla ekler. Belirtilen dosya mevcut değilse, oluşturulur. Tüm dizeler yazıldıktan sonra dosya kapatılır.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Dizelerin ekleneceği dosyanın yolu |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Dosyaya yazılacak dizeler |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kullanılacak karakter kodlaması |

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Tip Tanımı [EncodingPtr](../../../system/encodingptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [IEnumerable](../../../system.collections.generic/ienumerable/)
* Sınıf [File](../)
* Ad Alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)