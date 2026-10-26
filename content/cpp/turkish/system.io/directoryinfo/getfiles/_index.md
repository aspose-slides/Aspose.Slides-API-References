---
title: GetFiles()
second_title: Aspose.Slides için C++ API Referansı
description: Mevcut nesne tarafından temsil edilen dizinde bulunan tüm dizinleri temsil eden FileInfo nesnelerine ortak işaretçiler içeren bir dizi döndürür.
type: docs
weight: 157
url: /tr/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() yöntemi


Returns an array containing shared pointers to [FileInfo](../../fileinfo/) objects representing all directories located in the directory represented by the current object.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) yöntemi


Searches for the files that satisfy the specified search criteria in the directory represented by the current object.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | The name pattern of the files to search for |

### Dönüş Değeri

An array of shared pointers to [FileInfo](../../fileinfo/) objects representing the found files whose names match **searchPattern**

## DirectoryInfo::GetFiles(const String\&, SearchOption) yöntemi


Searches for the files that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | The name pattern of the files to search for |
| searchOption | [SearchOption](../../searchoption/) | Specifies whether the search has to be performed in the directory represented by the current object only or in the whole directory tree rooted in the directory represented by the current object |

### Dönüş Değeri

An array of shared pointers to [FileInfo](../../fileinfo/) objects representing the found files whose names match **searchPattern**

## Ayrıca Bakınız

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Sınıf [DirectoryInfo](../)
* Sınıf [String](../../../system/string/)
* AdAlanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)