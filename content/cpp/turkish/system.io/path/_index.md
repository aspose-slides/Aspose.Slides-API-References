---
title: Path
second_title: Aspose.Slides için C++ API Referansı
description: Yolları yönetmek için yöntemler sağlar. Bu, örnek hizmeti olmayan statik bir tiptir. Asla herhangi bir şekilde onun örneklerini oluşturmamalısınız.
type: docs
weight: 339
url: /tr/system.io/path/
---
## Path sınıfı

Yolları yönetmek için yöntemler sağlar. Bu, örnek hizmeti olmayan statik bir tiptir. Asla herhangi bir şekilde onun örneklerini oluşturmamalısınız.

```cpp
class Path
```

## Yöntemler

| Metod | Açıklama |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen dosya yolundaki uzantıyı değiştirir. |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Belirtilen yolun geçerli olup olmadığını, geçersiz karakterler içerip içermediğini kontrol ederek belirler. Yol geçersiz karakterler içeriyorsa bir istisna fırlatılır. |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Belirtilen yol bölümlerini tek bir yola birleştirir; gerekirse bölümler arasına dizin ayırıcı karakterler ekler. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | İki belirtilen yol bölümünü tek bir yola birleştirir; gerekirse bölümler arasına dizin ayırıcı karakter ekler. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Üç belirtilen yol bölümünü tek bir yola birleştirir; gerekirse bölümler arasına dizin ayırıcı karakterler ekler. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Dört belirtilen yol bölümünü tek bir yola birleştirir; gerekirse bölümler arasına dizin ayırıcı karakterler ekler. |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | Belirtilen yolun referans verdiği dizinin adını döndürür. |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | Belirtilen yolun referans verdiği dosyanın uzantısını döndürür. |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | Belirtilen yolun referans verdiği dosyanın adını döndürür. |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | Belirtilen yolun referans verdiği dosyanın uzantısız adını döndürür. |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | Belirtilen yolu tam yola dönüştürür. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Dosya adlarında izin verilmeyen karakterleri içeren bir dizi döndürür. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | Yol adlarında izin verilmeyen karakterleri içeren bir dizi döndürür. |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | Belirtilen yolun kök dizinini döndürür. |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | Rastgele oluşturulmuş bir dosya adı döndürür. |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | Benzersiz bir ada sahip yeni bir dosya oluşturur ve ona tam yolu döndürür. |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | Benzersiz bir ada sahip yeni bir dosya oluşturur ve ona tam yolu döndürür. [GetTempFileName_()](./gettempfilename_/) yönteminin eş anlamlısıdır. |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | Geçerli kullanıcının geçici dizininin yolunu döndürür. |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | Belirtilen yolun uzantılı bir dosyaya referans verip vermediğini belirler. |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | Belirtilen yolun bir kök içerip içermediğini belirler. |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | Belirtilen yolu normalleştirir. |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | Belirtilen yolu temsil eden boost::filesystem::path sınıfının bir örneğini döndürür. |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | Belirtilen Boost yol nesnesinin dize temsili dönüşümünü döndürür. |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | Bir yol içinde dizin seviyelerini ayırmak için kullanılan alternatif bir karakter. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | Bir yol içinde dizin seviyelerini ayırmak için kullanılan bir karakter. |
| static [PathSeparator](./pathseparator/) | Ortam değişkenlerinde yol dizelerini ayırmak için kullanılan bir ayırıcı karakter. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | Bir birim ayırıcı karakter. |

## Notlar



```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Rastgele bir dosya adı oluştur.
  auto filename = Path::GetRandomFileName();

  // Dosya adı hakkında bilgi yazdır.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
Filename: qhuzkyqv.y6p
Filename w/o an extension: qhuzkyqv
Extension: .y6p
*/
```

## Bkz.

* Ad alanı [System::IO](../)
* Kütüphane [Aspose.Slides](../../)