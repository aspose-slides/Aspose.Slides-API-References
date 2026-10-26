---
title: MemoryStream()
second_title: Aspose.Slides for C++ API Referansı
description: MemoryStream sınıfının yeni bir örneğini, başlangıç kapasitesi 0 olacak şekilde oluşturur.
type: docs
weight: 1
url: /tr/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() yapıcı

Yeni bir [MemoryStream](../) sınıfının örneğini, başlangıç kapasitesi 0 olacak şekilde oluşturur.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) yapıcı

Yeni bir [MemoryStream](../) sınıfının örneğini, belirtilen boyutta bir bellek tamponuna dayalı bir akış temsil edecek şekilde oluşturur.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| capacity_ | int | Oluşturulan nesnenin temsil ettiği akışla ilişkili bir bellek tamponunun bayt cinsinden boyutu |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) yapıcı

Yeni bir [MemoryStream](../) sınıfının örneğini, belirtilen bellek tamponuna bağlanan bir bellek akışı olarak oluşturur. Bir parametre akışın yazılabilir olup olmadığını belirtir.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Oluşturulan nesnenin temsil ettiği akışın temel bellek tamponu olarak kullanılacak bir bayt dizisi |
| writable | **bool** | Akışın yazılabilir olup olmadığını belirtir |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) yapıcı

Yeni bir [MemoryStream](../) sınıfının örneğini, belirtilen bellekteki tamponun belirtilen indeksten başlayarak belirtilen sayıda öğeyi içeren bir segmentine bağlanan bir bellek akışı olarak oluşturur. Parametreler akışın yazılabilir olup olmadığını ve GetBytes() metodunun çağrılıp çağrılamayacağını belirtir.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bir bayt dizisinin bir bölümü, nesnenin temsil ettiği akışın temel bellek tamponu olarak kullanılacak |
| index | int | **content** içinde bölümü başlatan öğenin 0 tabanlı indeksi |
| count | int | **content** içinde bölüme dahil edilecek öğe sayısı |
| writable | **bool** | Akışın yazılabilir olup olmadığını belirtir |
| publiclyVisible | **bool** | GetByte() metodunun çağırana temeldeki bellek tamponunu sunup sunmayacağını belirtir |

## Diğer Bilgiler

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [MemoryStream](../)
* Ad Alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)