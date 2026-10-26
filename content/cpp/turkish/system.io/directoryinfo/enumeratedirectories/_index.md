---
title: EnumerateDirectories()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dizinleri içeren yinelemeli bir koleksiyon döndürür.
type: docs
weight: 105
url: /tr/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() metod

Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dizinleri içeren yinelemeli bir koleksiyon döndürür.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) metod

Geçerli nesne tarafından temsil edilen dizinde belirtilen arama kriterlerini karşılayan dizinleri arar.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Aranacak dizinlerin ad deseni |

### Dönüş Değeri

Bulunan dizinleri temsil eden ve adı **searchPattern** ile eşleşen [DirectoryInfo](../) nesnelerine ortak işaretçilerin yinelemeli koleksiyonu

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) metod

Geçerli nesne tarafından temsil edilen dizinde ya da geçerli nesne tarafından temsil edilen dizinden kök alıp tüm dizin ağacında belirtilen arama kriterlerini karşılayan dizinleri arar.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Aranacak dizinlerin ad deseni |
| searchOption | [SearchOption](../../searchoption/) | Aramanın yalnızca geçerli nesne tarafından temsil edilen dizinde mi yoksa bu nesne tarafından temsil edilen dizinden kök alan bütün dizin ağacında mı gerçekleştirileceğini belirtir |

### Dönüş Değeri

Bulunan dizinleri temsil eden ve adı **searchPattern** ile eşleşen [DirectoryInfo](../) nesnelerine ortak işaretçilerin yinelemeli koleksiyonu

## Ayrıca Bakınız

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)