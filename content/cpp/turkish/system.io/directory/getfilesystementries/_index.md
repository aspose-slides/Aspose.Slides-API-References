---
title: GetFileSystemEntries()
second_title: Aspose.Slides C++ için API Referansı
description: Belirtilen dizinde veya belirtilen dizinde köklenen tüm dizin ağacında, belirtilen arama kriterlerini karşılayan dosya ve dizinleri arar.
type: docs
weight: 92
url: /tr/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String&, const String&, SearchOption) metod

Belirtilen dizinde veya belirtilen dizinde köklenen tüm dizin ağacında, belirtilen arama kriterlerini karşılayan dosya ve dizinleri arar.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | Aranacak dizine tam ya da göreceli yol |
| searchPattern | const [String](../../../system/string/)& | Aranacak dosya ve dizinlerin ad deseni |
| searchOption | [SearchOption](../../searchoption/) | Aramanın yalnızca belirtilen dizinde mi yoksa belirtilen dizinde köklenen tüm dizin ağacında mı yapılacağını belirtir |

### Dönüş Değeri

**searchPattern** ile eşleşen bulunan dosya ve dizinlerin tam yollarından oluşan bir dizi

## Ayrıca Bakınız

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)