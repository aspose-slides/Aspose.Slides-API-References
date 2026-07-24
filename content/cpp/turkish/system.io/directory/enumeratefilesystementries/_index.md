---
title: EnumerateFileSystemEntries()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizinde ya da belirtilen dizini kök alan bütün dizin ağacında, belirtilen arama kriterlerini karşılayan dosya ve dizinleri arar.
type: docs
weight: 53
url: /tr/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries(const String&, const String&, SearchOption) method

Arama kriterlerini karşılayan dosya ve dizinleri, belirtilen dizinde ya da belirtilen dizini kök alan bütün dizin ağacında arar.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | Arama yapılacak dizinin tam veya göreceli yolu |
| searchPattern | const [String](../../../system/string/)& | Aranacak dosya ve dizinlerin ad deseni |
| searchOption | [SearchOption](../../searchoption/) | Aramanın yalnızca belirtilen dizinde mi yoksa belirtilen dizini kök alan bütün dizin ağacında mı yapılacağını belirtir |

### Dönüş Değeri

İsimleri **searchPattern** ile eşleşen bulunan dosya ve dizinlerin tam yollarının yineleyebilir koleksiyonu

## Ayrıca Bakınız

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [Directory](../)
* Ad Alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)