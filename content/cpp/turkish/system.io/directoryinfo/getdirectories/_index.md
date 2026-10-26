---
title: GetDirectories()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli nesne tarafından temsil edilen dizinde konumlanan tüm alt dizinleri temsil eden DirectoryInfo nesnelerine ortak işaretçiler içeren bir dizi döndürür.
type: docs
weight: 144
url: /tr/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() metodu


Geçerli nesne tarafından temsil edilen dizindeki tüm alt dizinleri temsil eden [DirectoryInfo](../) nesnelerine ortak işaretçiler içeren bir dizi döndürür.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) metodu


Geçerli nesne tarafından temsil edilen dizinde belirtilen arama kriterlerini karşılayan dizinleri arar.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Aranacak dizinlerin ad deseni |

### Dönüş Değeri

**searchPattern** ile eşleşen adlara sahip bulunan dizinleri temsil eden [DirectoryInfo](../) nesnelerine ortak işaretçiler içeren bir dizi

## DirectoryInfo::GetDirectories(const String\&, SearchOption) metodu


Geçerli nesne tarafından temsil edilen dizinde ya da geçerli nesne tarafından temsil edilen dizinin kök olduğu tüm dizin ağacında belirtilen arama kriterlerini karşılayan dizinleri arar.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Aranacak dizinlerin ad deseni |
| searchOption | [SearchOption](../../searchoption/) | Aramanın yalnızca geçerli nesne tarafından temsil edilen dizinde mi yoksa geçerli nesne tarafından temsil edilen dizinin kök olduğu tüm dizin ağacında mı yapılacağını belirler |

### Dönüş Değeri

**searchPattern** ile eşleşen adlara sahip bulunan dizinleri temsil eden [DirectoryInfo](../) nesnelerine ortak işaretçiler içeren bir dizi

## İlgili

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)