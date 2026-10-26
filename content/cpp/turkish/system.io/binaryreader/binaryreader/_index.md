---
title: BinaryReader()
second_title: Aspose.Slides for C++ API Referansı
description: BinaryReader sınıfının, belirtilen akıştan UTF-8 kodlamasını kullanarak veri okuyan bir örneğini oluşturur.
type: docs
weight: 1
url: /tr/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) yapıcı


[BinaryReader](../) sınıfının bir örneğini oluşturur; belirtilen akıştan UTF-8 kodlamasını kullanarak veri okur.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Giriş akışı |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) yapıcı


[BinaryReader](../) sınıfının bir örneğini oluşturur; belirtilen akıştan belirtilen kodlamayı kullanarak veri okur.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Giriş akışı |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kullanılacak kodlama |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) yapıcı


[BinaryReader](../) sınıfının bir örneğini oluşturur; belirtilen akıştan belirtilen kodlamayı kullanarak veri okur.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Giriş akışı |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kullanılacak kodlama |
| leaveOpen | **bool** | Mevcut nesne atıldıktan sonra **input** akışının açık bırakılıp bırakılmayacağını (true) belirtir, aksi takdirde (false) |

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [Stream](../../stream/)
* Sınıf [BinaryReader](../)
* Sınıf [Encoding](../../../system.text/encoding/)
* Ad Alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)