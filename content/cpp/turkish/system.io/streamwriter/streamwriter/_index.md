---
title: StreamWriter()
second_title: Aspose.Slides for C++ API Referansı
description: StreamWriter nesnesinin bir örneğini oluşturur; bu nesne, belirtilen temel akışa UTF-8 kodlaması ve varsayılan 1024 bayt boyutundaki bir tampon kullanarak karakter yazar.
type: docs
weight: 1
url: /tr/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) yapıcı

Belirtilen temel akışa UTF-8 kodlaması ve varsayılan 1024 bayt boyutundaki bir tampon kullanarak karakter yazan [StreamWriter](../) nesnesinin bir örneğini oluşturur.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Karakterlerin yazılacağı temel akış |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) yapıcı

Belirtilen temel akışa belirtilen kodlamayı ve varsayılan 1024 bayt boyutundaki bir tamponu kullanarak karakter yazan [StreamWriter](../) nesnesinin bir örneğini oluşturur.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Karakterlerin yazılacağı temel akış |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kullanılacak kodlama |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) yapıcı

Belirtilen temel akışa belirtilen kodlamayı ve belirtilen boyutta bir tamponu kullanarak karakter yazan [StreamWriter](../) nesnesinin bir örneğini oluşturur. Bir parametre, [StreamWriter](../) nesnesi yok edildiğinde temel akışın kapatılıp kapatılmayacağını belirtir.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Karakterlerin yazılacağı temel akış |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kullanılacak kodlama |
| buffer_size | int | Tamponun en az byte cinsinden boyutu |
| leave_open | **bool** | Mevcut [StreamWriter](../) nesnesi yok edildikten sonra temel akışın açık bırakılıp bırakılmayacağını belirtir |

## StreamWriter::StreamWriter(const String\&) yapıcı

Belirtilen dosyaya UTF-8 kodlaması ve varsayılan 1024 bayt boyutundaki bir tampon kullanarak karakter yazan [StreamWriter](../) nesnesinin bir örneğini oluşturur.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Karakterlerin yazılacağı dosyanın yolu |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) yapıcı

Belirtilen dosyaya belirtilen kodlamayı ve varsayılan 1024 bayt boyutundaki bir tamponu kullanarak karakter yazan [StreamWriter](../) nesnesinin bir örneğini oluşturur. Bir parametre, verilerin dosyaya eklenip eklenmeyeceğini veya dosyanın üzerine yazılıp yazılmayacağını belirtir.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Karakterlerin yazılacağı dosyanın yolu |
| append | **bool** | Verilerin belirtilen dosyaya eklenip eklenmeyeceğini (true) ya da dosyanın üzerine yazılıp yazılmayacağını (false) belirtir |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kullanılacak kodlama |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) yapıcı

Belirtilen dosyaya belirtilen kodlamayı ve belirtilen tampon boyutunu kullanarak karakter yazan [StreamWriter](../) nesnesinin bir örneğini oluşturur. Bir parametre, verilerin dosyaya eklenip eklenmeyeceğini veya dosyanın üzerine yazılıp yazılmayacağını belirtir.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Karakterlerin yazılacağı dosyanın yolu |
| append | **bool** | Verilerin belirtilen dosyaya eklenip eklenmeyeceğini (true) ya da dosyanın üzerine yazılıp yazılmayacağını (false) belirtir |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kullanılacak kodlama |
| buffer_size | int | Kullanılacak tamponun boyutu |

## Başvurular

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)