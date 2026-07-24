---
title: EnumerateFiles()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dosyaları içeren yinelenebilir bir koleksiyon döndürür.
type: docs
weight: 118
url: /tr/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() metot


Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dosyaları içeren yinelenebilir bir koleksiyon döndürür.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) metot


Geçerli nesne tarafından temsil edilen dizinde, belirtilen arama kriterlerini karşılayan dosyaları arar.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Aranacak dosyaların isim deseni |

### Dönüş Değeri

İsimleri **searchPattern** ile eşleşen bulunan dosyaları temsil eden [FileInfo](../../fileinfo/) nesnelerine ortak işaretçilerin bulunduğu yinelenebilir koleksiyon.

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) metot


Geçerli nesne tarafından temsil edilen dizinde ya da bu dizinden kök alan tüm dizin ağacında, belirtilen arama kriterlerini karşılayan dosyaları arar.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Aranacak dosyaların isim deseni |
| searchOption | [SearchOption](../../searchoption/) | Aramanın sadece geçerli nesne tarafından temsil edilen dizinde mi yoksa bu nesne tarafından temsil edilen dizinden kök alan tüm dizin ağacında mı yapılacağını belirtir |

### Dönüş Değeri

İsimleri **searchPattern** ile eşleşen bulunan dosyaları temsil eden [FileInfo](../../fileinfo/) nesnelerine ortak işaretçilerin bulunduğu yinelenebilir koleksiyon.

## İlgili

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)