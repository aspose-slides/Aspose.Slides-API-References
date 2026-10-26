---
title: Add()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizeyi atomikleştirir ve NameTable'a ekler.
type: docs
weight: 14
url: /tr/system.xml/nametable/add/
---
## NameTable::Add(const String\&) yöntemi


Belirtilen dizeyi atomikleştirir ve [NameTable](../)'ye ekler.

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | Eklenecek dize. |

### Döndürülen Değer

Atomikleştirilmiş dize veya zaten [NameTable](../) içinde varsa mevcut dize.

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) yöntemi


Belirtilen dizeyi atomikleştirir ve [NameTable](../)'ye ekler.

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Eklenecek dizeyi içeren karakter dizisi. |
| start | **int32_t** | Dizedeki ilk karakteri belirten, diziye sıfır tabanlı indeks. |
| len | **int32_t** | Dizedeki karakter sayısı. |

### Döndürülen Değer

Atomikleştirilmiş dize veya [NameTable](../) içinde zaten mevcutsa mevcut dize. **len** sıfır ise, [String::Empty](../../../system/string/empty/) döndürülür.

## Diğer Bağlantılar

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [NameTable](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)