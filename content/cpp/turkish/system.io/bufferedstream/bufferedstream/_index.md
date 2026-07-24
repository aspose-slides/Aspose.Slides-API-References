---
title: BufferedStream()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen akışı saran ve 4096 bayt uzunluğunda bir tampon kullanan bir BufferedStream nesnesi oluşturur.
type: docs
weight: 1
url: /tr/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) yapıcı

Belirtilen akışı saran ve 4096 bayt uzunluğunda bir tampon kullanan bir [BufferedStream](../) nesnesi oluşturur.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Temel [Stream](../../stream/) nesnesi |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) yapıcı

Belirtilen akışı saran ve belirtilen boyutta bir tampon kullanan bir [BufferedStream](../) nesnesi oluşturur.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Temel [Stream](../../stream/) nesnesi |
| bufferSize | int | Tamponun bayt cinsinden boyutu |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Stream](../../stream/)
* Sınıf [BufferedStream](../)
* AdAlanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)