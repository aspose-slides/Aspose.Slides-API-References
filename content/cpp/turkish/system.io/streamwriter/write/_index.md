---
title: Write()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen karakteri akışa yazar.
type: docs
weight: 79
url: /tr/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) metodu

Belirtilen karakteri akışa yazar.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char_t | Yazılacak karakter |

## StreamWriter::Write(const String\&) metodu

Belirtilen dizeyi akışa yazar.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Yazılacak dize |

## StreamWriter::Write(const SharedPtr\<Object\>\&) metodu

Belirtilen nesnenin dize temsilini akışa yazar.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Yazılacak nesne |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&) metodu

Belirtilen diziden tüm karakterleri akışa yazar.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Yazılacak karakterleri içeren dizi |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metodu

Belirtilen karakter dizisinden UTF-16 karakterlerinin belirli bir alt aralığını akışa yazar.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Yazılacak karakterleri içeren dizi |
| index | **int32_t** | **buffer** içinde yazılacak alt aralığın başladığı 0-tabanlı öğe indeksi |
| count | **int32_t** | Yazılacak alt aralıktaki karakter sayısı; -1 değeri alt aralığın **buffer** dizisinin sonuna kadar sürdüğünü belirtir |

## StreamWriter::Write(const char_t *) metodu

Belirtilen C dizesini akışa yazar.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const char_t * | Yazılacak C dizesi |

## StreamWriter::Write(const System::SharedPtr\<T\>\&) metodu

Belirtilen nesnenin dize temsilini akışa yazar.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Nesnenin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | Yazılacak nesne |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [StreamWriter](../)
* Sınıf [String](../../../system/string/)
* Sınıf [Object](../../../system/object/)
* Ad alanı [System::IO](../../)
* Library [Aspose.Slides](../../../)