---
title: WriteLine()
second_title: Aspose.Slides için C++ API Referansı
description: Satır sonu karakterlerini akışa yazar.
type: docs
weight: 92
url: /tr/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() metodu


Akışa satır sonu karakterlerini yazar.

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) metodu


Belirtilen dizeyi, satır sonu karakterleriyle birlikte akışa yazar.

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Yazılacak dize |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) metodu


Belirtilen nesnenin dize temsilini, satır sonu karakterleriyle birlikte akışa yazar.

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Yazılacak nesne |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) metodu


Belirtilen diziden tüm karakterleri, satır sonu karakterleriyle birlikte akışa yazar.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Yazılacak karakterleri içeren dizi |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metodu


Belirtilen karakter dizisinden belirtilen UTF-16 karakter alt aralığını, satır sonu karakterleriyle birlikte akışa yazar.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Yazılacak karakterleri içeren dizi |
| index | **int32_t** | Yazma alt aralığının başladığı **buffer** içindeki 0 tabanlı indeks |
| count | **int32_t** | Yazılacak alt aralıktaki karakter sayısı; -1, alt aralığın **buffer** dizisinin sonuna kadar devam ettiğini belirtir. |

## StreamWriter::WriteLine(const char_t *) metodu


Belirtilen C dizesini, satır sonu karakterleriyle birlikte akışa yazar.

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const char_t * | Yazılacak C dizesi |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) metodu


Belirtilen nesnenin dize temsilini, satır sonu karakterleriyle birlikte akışa yazar.

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Nesnenin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | Yazılacak nesne |

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)