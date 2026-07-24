---
title: GetDirectories()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizinde veya belirtilen dizinde köklenen tüm dizin ağacında, belirtilen arama kriterlerini karşılayan dizinleri arar.
type: docs
weight: 66
url: /tr/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String\&, const String\&, SearchOption) metod

Belirtilen dizinde veya belirtilen dizinde köklenen tüm dizin ağacında belirtilen arama kriterlerini karşılayan dizinleri arar.

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Aranacak dizinin tam veya göreli yolu |
| searchPattern | const [String](../../../system/string/)\& | Aranacak dizinlerin ad deseni |
| searchOption | [SearchOption](../../searchoption/) | Aramanın yalnızca belirtilen dizinde mi yoksa belirtilen dizinde köklenen tüm dizin ağacında mı yapılacağını belirler |

### Dönüş Değeri

Bulunan dizinlerin, adları **searchPattern** ile eşleşen tam yol dizilerini içeren bir dizi

## Ayrıca Bakınız

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)