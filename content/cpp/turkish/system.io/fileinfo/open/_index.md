---
title: Open()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli nesne tarafından temsil edilen dosyayı belirtilen modda okuma ve yazma için, paylaşım olmaksızın açar.
type: docs
weight: 183
url: /tr/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) metod


Geçerli nesne tarafından temsil edilen dosyayı belirtilen modda okuma ve yazma için, paylaşım olmaksızın açar.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Dosyayı açmak için kullanılacak modu belirtir |

### Dönüş Değeri

Geçerli nesne tarafından temsil edilen dosyayla ilişkili bir [FileStream](../../filestream/) nesnesi

## FileInfo::Open(FileMode, FileAccess) metod


Geçerli nesne tarafından temsil edilen dosyayı belirtilen modda, belirtilen erişim türüyle ve paylaşım olmaksızın açar.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Dosyayı açmak için kullanılacak modu belirtir |
| access | [FileAccess](../../fileaccess/) | İstenen erişim türü |

### Dönüş Değeri

Geçerli nesne tarafından temsil edilen dosyayla ilişkili bir [FileStream](../../filestream/) nesnesi

## FileInfo::Open(FileMode, FileAccess, FileShare) metod


Geçerli nesne tarafından temsil edilen dosyayı belirtilen modda, belirtilen erişim türü ve paylaşım seçeneğiyle açar.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Dosyayı açmak için kullanılacak modu belirtir |
| access | [FileAccess](../../fileaccess/) | İstenen erişim türü |
| share | [FileShare](../../fileshare/) | Açılan dosyaya diğer [FileStream](../../filestream/) nesnelerinin sahip olduğu erişim türü |

### Dönüş Değeri

Geçerli nesne tarafından temsil edilen dosyayla ilişkili bir [FileStream](../../filestream/) nesnesi

## Bakınız

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)