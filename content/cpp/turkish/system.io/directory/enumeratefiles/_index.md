---
title: EnumerateFiles()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizinde ya da belirtilen dizinin köküne sahip tüm dizin ağacında, belirtilen arama kriterlerini karşılayan dosyaları arar.
type: docs
weight: 40
url: /tr/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String\&, const String\&, SearchOption) metodu

Belirtilen dizinde ya da belirtilen dizinin köküne sahip tüm dizin ağacında, belirtilen arama kriterlerini karşılayan dosyaları arar.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Aranacak dizinin tam ya da göreli yolu |
| searchPattern | const [String](../../../system/string/)\& | Aranacak dosyaların ad kalıbı |
| searchOption | [SearchOption](../../searchoption/) | Aramanın yalnızca belirtilen dizinde mi yoksa belirtilen dizinin köküne sahip tüm dizin ağacında mı yapılacağını belirtir |

### Dönüş Değeri

Adları **searchPattern** ile eşleşen bulunan dosyaların tam yollarının enumerable koleksiyonu

## İlgili

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)