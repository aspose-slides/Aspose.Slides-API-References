---
title: GetFileSystemInfos()
second_title: C++ için Aspose.Slides API Referansı
description: Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dosya ve dizinleri temsil eden FileSystemInfo nesnelerine ortak işaretçiler içeren bir dizi döndürür.
type: docs
weight: 170
url: /tr/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() method

Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dosya ve dizinleri temsil eden [FileSystemInfo](../../filesysteminfo/) nesnelerine ortak işaretçiler içeren bir dizi döndürür.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) method

Geçerli nesne tarafından temsil edilen dizinde belirtilen arama kriterlerini karşılayan dosya ve dizinleri arar.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Aranacak dosya ve dizinlerin ad deseni |

### Dönüş Değeri

İsimleri **searchPattern** ile eşleşen bulunan dosya ve dizinleri temsil eden [FileSystemInfo](../../filesysteminfo/) nesnelerine ortak işaretçiler içeren bir dizi.

## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) method

Geçerli nesne tarafından temsil edilen dizinde ya da bu nesnenin temsil ettiği dizinden köklenen tüm dizin ağacında belirtilen arama kriterlerini karşılayan dosya ve dizinleri arar.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Aranacak dosya ve dizinlerin ad deseni |
| searchOption | [SearchOption](../../searchoption/) | Aramanın yalnızca geçerli nesne tarafından temsil edilen dizinde mi yoksa bu nesnenin temsil ettiği dizinden köklenen tüm dizin ağacında mı gerçekleştirilmesi gerektiğini belirler |

### Dönüş Değeri

İsimleri **searchPattern** ile eşleşen bulunan dosya ve dizinleri temsil eden [FileSystemInfo](../../filesysteminfo/) nesnelerine ortak işaretçiler içeren bir dizi.

## İlgili

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)