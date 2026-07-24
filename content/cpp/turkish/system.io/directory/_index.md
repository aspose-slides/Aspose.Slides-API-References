---
title: Directory
second_title: Aspose.Slides for C++ API Referansı
description: Dizinleri manipüle etmek için yöntemler içerir. Bu, örnek hizmeti olmayan statik bir türdür. Hiçbir şekilde onun örneklerini oluşturmamalısınız.
type: docs
weight: 235
url: /tr/system.io/directory/
---
## Directory sınıfı

Dizinleri manipüle etmek için yöntemler içerir. Bu, örnek hizmeti olmayan statik bir türdür. Herhangi bir şekilde onun örneklerini oluşturmamalısınız.

```cpp
class Directory
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | Belirtilen yol içinde, mevcut değillerse, tüm dizinleri oluşturur. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | Belirtilen dosyayı veya dizini kaldırır. İstisna fırlatmaz. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Belirtilen dizinde veya belirtilen dizinde köklenen tüm dizin ağacında, belirtilen arama kriterlerini karşılayan dizinleri arar. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Belirtilen dizinde veya belirtilen dizinde köklenen tüm dizin ağacında, belirtilen arama kriterlerini karşılayan dosyaları arar. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Belirtilen dizinde veya belirtilen dizinde köklenen tüm dizin ağacında, belirtilen arama kriterlerini karşılayan dosya ve dizinleri arar. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Belirtilen yolun mevcut bir dizine işaret edip etmediğini belirler. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Belirtilen varlığın oluşturulma zamanını yerel zaman olarak döndürür. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Belirtilen varlığın oluşturulma zamanını UTC zamanı olarak döndürür. |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | Geçerli dizinin tam adını (yolu dahil) döndürür. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Belirtilen dizinde veya belirtilen dizinde köklenen tüm dizin ağacında, belirtilen arama kriterlerini karşılayan dizinleri arar. |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | Belirtilen yolun kök dizinini döndürür. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Belirtilen dizinde veya belirtilen dizinde köklenen tüm dizin ağacında, belirtilen arama kriterlerini karşılayan dosyaları arar. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Belirtilen dizinde veya belirtilen dizinde köklenen tüm dizin ağacında, belirtilen arama kriterlerini karşılayan dosya ve dizinleri arar. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Belirtilen varlığın son erişim zamanını yerel zaman olarak döndürür. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Belirtilen varlığın son erişim zamanını UTC zamanı olarak döndürür. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Belirtilen varlığın son yazma zamanını yerel zaman olarak döndürür. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Belirtilen varlığın son yazma zamanını UTC zamanı olarak döndürür. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | UYGULANMADI. |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | Belirtilen varlığın ana dizinini temsil eden [DirectoryInfo](../directoryinfo/) nesnesine bir paylaşımlı işaretçi döndürür. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen varlığı yeni konuma taşır. Taşınacak varlık bir dizinse, tüm içeriğiyle birlikte taşınır. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Belirtilen varlığın oluşturulma zamanını yerel zaman olarak ayarlar. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Belirtilen varlığın oluşturulma zamanını UTC zamanı olarak ayarlar. |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | Geçerli dizini ayarlar. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Belirtilen varlığın son erişim zamanını yerel zaman olarak ayarlar. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Belirtilen varlığın son erişim zamanını UTC zamanı olarak ayarlar. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Belirtilen varlığın son yazma zamanını yerel zaman olarak ayarlar. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Belirtilen varlığın son yazma zamanını UTC zamanı olarak ayarlar. |

## Typedef'ler

| Typedef | Açıklama |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | [String](../../system/string/) nesnelerinden oluşan bir küme üzerinde yineleme yapan IEnumerable nesnesine bir paylaşımlı işaretçi için bir takma isim. |

## Açıklamalar



```cpp
#include "system/io/directory.h"
#include "system/io/path.h"
#include "system/string.h"
#include <iostream>

void PrintMessage(const System::String &path)
{
  std::cout << "Directory '" << path << (System::IO::Directory::Exists(path) ? "' exists." : "' doesn't exist.") << std::endl;
}

int main()
{
  // Dizin yollarını içeren string'leri oluşturur.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // Dizinlerin var olup olmadığını kontrol eder.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // Temp dizin bilgilerini yazdırır.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
Dizin 'C:\' var.
Dizin 'C:\Some directory' mevcut değil.
Dizin 'C:\Users\lanor\AppData\Local\Temp\' var.
Oluşturma Zamanı: 27.08.2021 14:21:42
Son Erişim Zamanı: 07.10.2021 12:16:41
Son Yazma Zamanı: 07.10.2021 12:16:41
*/
```

## İlgili Bakınız

* Ad Alanı [System::IO](../)
* Kütüphane [Aspose.Slides](../../)