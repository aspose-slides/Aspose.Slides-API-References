---
title: BinaryWriter()
second_title: C++ için Aspose.Slides API Referansı
description: Belirtilen kodlamayı kullanarak belirtilen akışa veri yazan BinaryWriter sınıfının bir örneğini oluşturur.
type: docs
weight: 1
url: /tr/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) yapıcı

Belirtilen kodlamayı kullanarak belirtilen akışa veri yazan [BinaryWriter](../) sınıfının bir örneğini oluşturur.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Çıktı akışı |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kullanılacak kodlama |
| leaveopen | **bool** | Geçerli nesne imha edildikten sonra **stream** akışının açık bırakılıp bırakılmayacağını (true) belirler; bırakılmayacaksa (false) |

## Bakınız

* Tip tanımı [StreamPtr](../../../system/streamptr/)
* Tip tanımı [EncodingPtr](../../../system/encodingptr/)
* Sınıf [BinaryWriter](../)
* Ad alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)