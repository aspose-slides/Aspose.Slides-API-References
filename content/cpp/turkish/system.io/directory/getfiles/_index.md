---
title: GetFiles()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizinde veya belirtilen dizinde köklenen tüm dizin ağacında, belirtilen arama ölçütlerini karşılayan dosyaları arar.
type: docs
weight: 79
url: /tr/system.io/directory/getfiles/
---
## Directory::GetFiles(const String\&, const String\&, SearchOption) yöntem

Belirtilen dizinde veya belirtilen dizinde köklenen tüm dizin ağacında, belirtilen arama ölçütlerini karşılayan dosyaları arar.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Aranacak dizine tam veya göreli yol |
| searchPattern | const [String](../../../system/string/)\& | Aranacak dosyaların ad kalıbı |
| searchOption | [SearchOption](../../searchoption/) | Aramanın yalnızca belirtilen dizinde mi yoksa belirtilen dizinde köklenen tüm dizin ağacında mı gerçekleştirilmesi gerektiğini belirler |

### Dönüş Değeri

İsimleri **searchPattern** ile eşleşen bulunan dosyaların tam yollarından oluşan bir dizi

## Bakınız

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [Directory](../)
* Ad alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)