---
title: FileStream()
second_title: Aspose.Slides for C++ API Referansı
description: FileStream sınıfının yeni bir örneğini oluşturur ve belirtilen parametrelerle başlatır.
type: docs
weight: 1
url: /tr/system.io/filestream/filestream/
---
## FileStream::FileStream(const String\&, FileMode) yapıcı

Constructs a new instance of [FileStream](../) class and initializes it with the specified parameters.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Açılacak dosyanın yolu. |
| mode | [FileMode](../../filemode/) | Dosyanın açılacağı modu belirtir. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) yapıcı

Constructs a new instance of [FileStream](../) class and initializes it with the specified parameters.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Açılacak dosyanın yolu. |
| mode | [FileMode](../../filemode/) | Dosyanın açılacağı modu belirtir. |
| access | [FileAccess](../../fileaccess/) | İstenen erişim türü. |
| share | [FileShare](../../fileshare/) | Diğer [FileStream](../) nesnelerinin açılan dosyaya sahip olduğu erişim türü. |
| buffer_size | **int32_t** | Okuma ve yazma işlemleri sırasında arabelleklenen bayt sayısı. |
| options | [FileOptions](../../fileoptions/) | Ek seçenekler. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) yapıcı

Constructs a new instance of [FileStream](../) class and initializes it with the specified parameters.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Açılacak dosyanın yolu. |
| mode | [FileMode](../../filemode/) | Dosyanın açılacağı modu belirtir. |
| access | [FileAccess](../../fileaccess/) | İstenen erişim türü. |
| share | [FileShare](../../fileshare/) | Diğer [FileStream](../) nesnelerinin açılan dosyaya sahip olduğu erişim türü. |
| buffer_size | **int32_t** | Okuma ve yazma işlemleri sırasında arabelleklenen bayt sayısı. |
| useAsync | **bool** | Asenkron G/Ç mi yoksa senkron G/Ç mi kullanılacağını belirtir. |
## Açıklamalar

Altta yatan işletim sistemi asenkron G/Ç'yi desteklemeyebilir.

## FileStream::FileStream(const FileStream\&) yapıcı

```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## Ayrıca Bakınız

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Sınıf [String](../../../system/string/)
* Sınıf [FileStream](../)
* Ad Alanı [System::IO](../../)
* Library [Aspose.Slides](../../../)