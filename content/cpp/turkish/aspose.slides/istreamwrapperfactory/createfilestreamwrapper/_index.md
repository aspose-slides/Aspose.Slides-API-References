---
title: CreateFileStreamWrapper()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen yol ve oluşturma modu ile FileStream oluşturur.
type: docs
weight: 14
url: /tr/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) metodu


Belirtilen yol ve oluşturma modu ile FileStream oluşturur.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Dosya adı [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Dosya modu [System::IO::FileMode](../../../system.io/filemode/) |

### Dönüş Değeri

COM arayüzü [IStreamWrapper](../../istreamwrapper/) için akış sarmalayıcısı

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) metodu


Belirtilen yol, oluşturma modu ve okuma/yazma izni ile FileStream oluşturur.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Dosya adı [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Dosya modu [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | Dosya erişimi [System::IO::FileAccess](../../../system.io/fileaccess/) |

### Dönüş Değeri

COM arayüzü [IStreamWrapper](../../istreamwrapper/) için akış sarmalayıcısı

## İlgili

* Enum [FileMode](../../../system.io/filemode/)
* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IStreamWrapper](../../istreamwrapper/)
* Sınıf [String](../../../system/string/)
* Sınıf [IStreamWrapperFactory](../)
* İsim Uzayı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)