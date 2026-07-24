---
title: EnumerateFileSystemInfos()
second_title: Aspose.Slides için C++ API Referansı
description: Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dosya ve dizinleri içeren yinelenebilir bir koleksiyon döndürür.
type: docs
weight: 131
url: /tr/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() metod


Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dosya ve dizinleri içeren yinelenebilir bir koleksiyon döndürür.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) metod


Geçerli nesne tarafından temsil edilen dizinde, belirtilen arama kriterlerini karşılayan dosya ve dizinleri arar.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Aranacak dosya ve dizinlerin ad kalıbı |

### Dönüş Değeri

İsimleri **searchPattern** ile eşleşen bulunan dosya ve dizinleri temsil eden [FileSystemInfo](../../filesysteminfo/) nesnelerine ortak işaretçileri içeren yinelenebilir koleksiyon

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) metod


Geçerli nesne tarafından temsil edilen dizinde veya geçerli nesne tarafından temsil edilen dizinin kök dizin ağacındaki tüm dizinde, belirtilen arama kriterlerini karşılayan dosya ve dizinleri arar.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Aranacak dosya ve dizinlerin ad kalıbı |
| searchOption | [SearchOption](../../searchoption/) | Aramanın yalnızca geçerli nesne tarafından temsil edilen dizinde mi yoksa geçerli nesne tarafından temsil edilen dizinin kök dizin ağacında mı yapılacağını belirler |

### Dönüş Değeri

İsimleri **searchPattern** ile eşleşen bulunan dosya ve dizinleri temsil eden [FileSystemInfo](../../filesysteminfo/) nesnelerine ortak işaretçileri içeren yinelenebilir koleksiyon

## İlgili

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)