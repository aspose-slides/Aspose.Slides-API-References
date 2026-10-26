---
title: File
second_title: Aspose.Slides for C++ API Referansı
description: Dosyaları işlemek için yöntemler sağlar. Bu, örnek hizmeti olmayan statik bir türdür. Hiçbir şekilde onun örneklerini oluşturmamalısınız.
type: docs
weight: 261
url: /tr/system.io/file/
---
## File sınıfı

Provides methods for manipulating files. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class File
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Belirtilen karakter kodlamasını kullanarak, belirtilen dize koleksiyonundaki dizeleri belirtilen dosyaya her satıra bir dize yazarak ekler. Belirtilen dosya yoksa, oluşturulur. Tüm dizeler yazıldıktan sonra dosya kapatılır. |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Belirtilen karakter kodlamasını kullanarak, belirtilen dizeyi belirtilen dosyaya ekler. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | Belirtilen dosyaya UTF-8 kodlamasıyla metin ekleyen bir [StreamWriter](../streamwriter/) nesnesi oluşturur. Belirtilen dosya yoksa, oluşturulur. |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Belirtilen dosyayı belirtilen konuma kopyalar. Hedef dosya zaten varsa, bir parametre onun üzerine yazılıp yazılmayacağını belirler. |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | Belirtilen tampon boyutu ve seçenekleri kullanarak yeni bir dosya oluşturur (veya mevcut dosyanın üzerine yazar) ve dosyayı okuma-yazma erişimi için açar. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | UTF-8 kodlamalı metin yazmak için yeni bir dosya oluşturur ya da mevcut dosyayı açar. |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | UYGULANMADI. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | Belirtilen dosya ya da dizini siler. |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | UYGULANMADI. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Belirtilen yolun mevcut bir dosyaya işaret edip etmediğini belirler. |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | Belirtilen varlığın özniteliklerini döndürür. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Belirtilen varlığın oluşturulma zamanını yerel saat olarak döndürür. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Belirtilen varlığın oluşturulma zamanını UTC saat olarak döndürür. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Belirtilen varlığın son erişim zamanını yerel saat olarak döndürür. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Belirtilen varlığın son erişim zamanını UTC saat olarak döndürür. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Belirtilen varlığın son yazma zamanını yerel saat olarak döndürür. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Belirtilen varlığın son yazma zamanını UTC saat olarak döndürür. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen dosyayı yeni konuma taşır. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | Belirtilen dosyayı belirtilen modda okuma-yazma için açar ve paylaşıma izin vermez. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Belirtilen dosyayı belirtilen modda, belirtilen erişim türü ve paylaşım seçeneğiyle açar. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | Belirtilen dosyayı yalnızca okuma için, 'Open' modunda ve okuma için paylaşımlı erişimle açar. |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Belirtilen mevcut dosyayı UTF-8 kodlamasıyla metin okuma amacıyla, paylaşım olmadan açar. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | Belirtilen dosyayı yalnızca yazma için, 'OpenOrCreate' modunda ve paylaşım olmadan açar. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | Belirtilen ikili dosyanın içeriğini bir bayt dizisine okur. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Belirtilen metin dosyasının içeriğini belirtilen karakter kodlamasını kullanarak satır satır bir dize dizisine okur. |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Belirtilen metin dosyasının içeriğini belirtilen karakter kodlamasını kullanarak tek bir [String](../../system/string/) nesnesine okur. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Belirtilen metin dosyasının içeriğini belirtilen karakter kodlamasını kullanarak satır satır okur ve her satırı temsil eden dize koleksiyonunu enumerable olarak döndürür. |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Bir dosyanın içeriğini diğer dosyayla değiştirir ve değiştirilen dosyanın bir yedeğini oluşturur. |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | Belirtilen dosyaya belirtilen öznitelikleri ayarlar. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | UYGULANMADI. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | UYGULANMADI. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | UYGULANMADI. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | UYGULANMADI. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Belirtilen varlığın son yazma zamanını yerel saat olarak ayarlar. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Belirtilen varlığın son yazma zamanını UTC saat olarak ayarlar. |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Belirtilen ikili dosyanın üzerine yazar ve belirtilen baytları ona yazar. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Yeni bir metin dosyası oluşturur ya da mevcut dosyanın üzerine yazar ve belirtilen enumerable dize koleksiyonundaki tüm dizeleri, her dizeyi yeni bir satıra yazarak, belirtilen kodlamayı kullanarak dosyaya yazar. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Yeni bir metin dosyası oluşturur ya da mevcut dosyanın üzerine yazar ve belirtilen dize dizisindeki tüm dizeleri, her dizeyi yeni bir satıra yazarak, belirtilen kodlamayı kullanarak dosyaya yazar. |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Yeni bir metin dosyası oluşturur ya da mevcut dosyanın üzerine yazar ve belirtilen dize içeriğini belirtilen kodlamayı kullanarak dosyaya yazar. |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Bir dosyadan okuma ve dosyaya yazma sırasında tamponlanan bayt sayısının varsayılan değeri. |

## Bakınız

* Ad alanı [System::IO](../)
* Kütüphane [Aspose.Slides](../../)