---
title: StreamReader()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen temel akıştan UTF-8 kodlamasını kullanarak ve varsayılan 1024 bayt boyutunda bir tamponla karakter okuyan StreamReader nesnesinin bir örneğini oluşturur.
type: docs
weight: 1
url: /tr/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) yapıcı


[StreamReader](../) nesnesinin bir örneğini oluşturur; belirtilen temel akıştan UTF-8 kodlamasını kullanarak ve varsayılan 1024 bayt boyutunda bir tamponla karakter okur.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Karakterlerin okunacağı temel akış |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) yapıcı


[StreamReader](../) nesnesinin bir örneğini oluşturur; belirtilen temel akıştan UTF-8 kodlamasını kullanarak ve varsayılan 1024 bayt boyutunda bir tamponla karakter okur. Bir parametre, bayt sırası işareti algılamanın etkinleştirilip etkinleştirilmeyeceğini belirtir.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Karakterlerin okunacağı temel akış |
| detectEncodingFromByteOrderMarks | **bool** | Akışın başında bayt sırası işaretlerini aramak için true, aksi takdirde false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) yapıcı


[StreamReader](../) nesnesinin bir örneğini oluşturur; belirtilen temel akıştan belirtilen kodlamayı kullanarak ve varsayılan 1024 bayt boyutunda bir tamponla karakter okur.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Karakterlerin okunacağı temel akış |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kullanılacak kodlama |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) yapıcı


[StreamReader](../) nesnesinin bir örneğini oluşturur; belirtilen temel akıştan belirtilen kodlamayı kullanarak ve varsayılan 1024 bayt boyutunda bir tamponla karakter okur. Bir parametre, bayt sırası işareti algılamanın etkinleştirilip etkinleştirilmeyeceğini belirtir.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Karakterlerin okunacağı temel akış |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kullanılacak kodlama |
| detectEncodingFromByteOrderMarks | **bool** | Akışın başında bayt sırası işaretlerini aramak için true, aksi takdirde false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) yapıcı


[StreamReader](../) nesnesinin bir örneğini oluşturur; belirtilen temel akıştan belirtilen kodlamayı kullanarak ve belirtilen boyutta bir tamponla karakter okur. Bir parametre, bayt sırası işareti algılamanın etkinleştirilip etkinleştirilmeyeceğini belirtir.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Karakterlerin okunacağı temel akış |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kullanılacak kodlama |
| detectEncodingFromByteOrderMarks | **bool** | Akışın başında bayt sırası işaretlerini aramak için true, aksi takdirde false |
| bufferSize | int | Tamponun minimum bayt cinsinden boyutu |

## StreamReader::StreamReader(const System::String\&) yapıcı


[StreamReader](../) nesnesinin bir örneğini oluşturur; belirtilen dosyadan UTF-8 kodlamasını kullanarak ve varsayılan 4096 bayt boyutunda bir tamponla karakter okur.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Karakterlerin okunacağı dosyanın yolu |

## StreamReader::StreamReader(const System::String\&, bool) yapıcı


[StreamReader](../) nesnesinin bir örneğini oluşturur; belirtilen dosyadan UTF-8 kodlamasını kullanarak ve varsayılan 4096 bayt boyutunda bir tamponla karakter okur. Bir parametre, bayt sırası işareti algılamanın etkinleştirilip etkinleştirilmeyeceğini belirtir.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Karakterlerin okunacağı dosyanın yolu |
| detectEncodingFromByteOrderMarks | **bool** | Dosyanın başında bayt sırası işaretlerini aramak için true, aksi takdirde false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) yapıcı


[StreamReader](../) nesnesinin bir örneğini oluşturur; belirtilen dosyadan belirtilen kodlamayı kullanarak ve varsayılan 4096 bayt boyutunda bir tamponla karakter okur.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Karakterlerin okunacağı dosyanın yolu |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kullanılacak kodlama |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) yapıcı


[StreamReader](../) nesnesinin bir örneğini oluşturur; belirtilen temel akıştan belirtilen kodlamayı kullanarak ve varsayılan 4096 bayt boyutunda bir tamponla karakter okur. Bir parametre, bayt sırası işareti algılamanın etkinleştirilip etkinleştirilmeyeceğini belirtir.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Karakterlerin okunacağı dosyanın yolu |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kullanılacak kodlama |
| detectEncodingFromByteOrderMarks | **bool** | Dosyanın başında bayt sırası işaretlerini aramak için true, aksi takdirde false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) yapıcı


[StreamReader](../) nesnesinin bir örneğini oluşturur; belirtilen dosyadan belirtilen kodlamayı kullanarak ve belirtilen boyutta bir tamponla karakter okur. Bir parametre, bayt sırası işareti algılamanın etkinleştirilip etkinleştirilmeyeceğini belirtir.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Karakterlerin okunacağı dosyanın yolu |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kullanılacak kodlama |
| detectEncodingFromByteOrderMarks | **bool** | Dosyanın başında bayt sırası işaretlerini aramak için true, aksi takdirde false |
| bufferSize | int | Tamponun minimum bayt cinsinden boyutu |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)