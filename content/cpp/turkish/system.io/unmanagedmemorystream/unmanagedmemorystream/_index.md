---
title: UnmanagedMemoryStream()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni bir UnmanagedMemoryStream örneği oluşturur.
type: docs
weight: 118
url: /tr/system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) yapıcı

Yeni bir [UnmanagedMemoryStream](../) örneği oluşturur.

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pointer | **uint8_t** * | Yönetilmeyen tampon için bir işaretçi |
| length | **int64_t** | Yönetilmeyen tamponun bayt cinsinden boyutu |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) yapıcı

Yeni bir [UnmanagedMemoryStream](../) örneği oluşturur.

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pointer | **uint8_t** * | Yönetilmeyen tampon için bir işaretçi |
| length | **int64_t** | Yönetilmeyen tamponun bayt cinsinden boyutu |
| capacity | **int64_t** | Akışa tahsis edilen toplam bellek miktarı |
| access | [FileAccess](../../fileaccess/) | Akışın yalnızca okuma, yalnızca yazma ya da her ikisi olarak kullanılacağını belirtir |

## Ayrıca Bakınız

* Enum [FileAccess](../../fileaccess/)
* Sınıf [UnmanagedMemoryStream](../)
* Ad alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)