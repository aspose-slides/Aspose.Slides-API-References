---
title: EnumerateDirectories()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizinde veya belirtilen dizinde köklenen tüm dizin ağacında, belirtilen arama kriterlerini karşılayan dizinleri arar.
type: docs
weight: 27
url: /tr/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String\&, const String\&, SearchOption) metod

Belirtilen dizinde veya belirtilen dizinde köklenen tüm dizin ağacında, belirtilen arama kriterlerini karşılayan dizinleri arar.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Aranacak dizine tam veya göreli yol |
| searchPattern | const [String](../../../system/string/)\& | Aranacak dizinlerin ad deseni |
| searchOption | [SearchOption](../../searchoption/) | Aramanın yalnızca belirtilen dizinde mi yoksa belirtilen dizinde köklenen tüm dizin ağacında mı gerçekleştirileceğini belirtir |

### Dönüş Değeri

**searchPattern** desenine uyan bulunan dizinlerin tam yollarının sürülebilir koleksiyonu

## Ayrıca

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)