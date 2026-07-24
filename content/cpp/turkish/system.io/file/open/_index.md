---
title: Open()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen dosyayı belirtilen kipte okuma ve yazma için, paylaşım olmadan açar.
type: docs
weight: 235
url: /tr/system.io/file/open/
---
## File::Open(const String\&, FileMode) metodu


Belirtilen dosyayı belirtilen kipte okuma ve yazma için, paylaşım olmadan açar.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Açılacak dosyanın yolu |
| mode | [FileMode](../../filemode/) | Dosyanın açılacağı modu belirtir |

### Dönüş Değeri

Açılan dosyayla ilişkili bir [FileStream](../../filestream/) nesnesi

## File::Open(const String\&, FileMode, FileAccess, FileShare) metodu


Belirtilen dosyayı belirtilen kipte, belirtilen erişim türü ve paylaşım seçeneği ile açar.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Açılacak dosyanın yolu |
| mode | [FileMode](../../filemode/) | Dosyanın açılacağı modu belirtir |
| access | [FileAccess](../../fileaccess/) | İstenen erişim türü |
| share | [FileShare](../../fileshare/) | Diğer [FileStream](../../filestream/) nesnelerinin açılan dosyaya sahip olduğu erişim türü |

### Dönüş Değeri

Açılan dosyayla ilişkili bir [FileStream](../../filestream/) nesnesi

## İlgili

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [File](../)
* Ad alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)