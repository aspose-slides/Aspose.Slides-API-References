---
title: Get()
second_title: Aspose.Slides for C++ API Referansı
description: Verilen tuple'ın N'inci öğesini almak için fonksiyon. Temel nesne için aşırı yükleme.
type: docs
weight: 2406
url: /tr/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) fonksiyon

Belirtilen tuple'ın N'inci öğesini almak için fonksiyon. Temel nesne için aşırı yükleme.

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| N | element index. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | incelemek için nesne. |

### Dönüş Değeri

N'inci tuple öğesinin nesneye dönüştürülmüş değeri.

## System::Get(const T\&) fonksiyon

Belirtilen tuple'ın N'inci öğesini almak için fonksiyon. Deconstruct yöntemi olan nesneler için aşırı yükleme.

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| N | element index. |
| T | type of inspected object. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| object | const T\& | incelemek için nesne. |

### Dönüş Değeri

N'inci tuple öğesinin değeri.

## System::Get(const SharedPtr\<T\>\&) fonksiyon

Belirtilen tuple'ın N'inci öğesini almak için fonksiyon. Paylaşımlı işaretçiler için aşırı yükleme.

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| N | element index. |
| T | type of inspected object. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | incelemek için nesne. |

### Dönüş Değeri

N'inci tuple öğesinin değeri.

## System::Get(T\&, const Index\&) fonksiyon

collection[index] ifadeleri için uygulama.

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Collection type. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| collection | T\& | Koleksiyon nesnesi. |
| index | const [Index](../index/)\& | [System.Index](../index/) tipinde öğe indeksi. |

### Dönüş Değeri

Hesaplanan offset'teki koleksiyon öğesi.

## System::Get(T\&, const Range\&) fonksiyon

Belirtilen aralıkla tanımlanan koleksiyonun bir dilimini döndürür.

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| collection | T\& | Dilimlenecek koleksiyon. |
| range | const [Range](../range/)\& | Dilim sınırlarını belirten aralık. |

### Dönüş Değeri

Hesaplanan başlangıç offset'i ve uzunluktan oluşan koleksiyonun bir görünümü veya dilimi.

## System::Get(const ValueTuple\<Args...\>\&) fonksiyon

Değer tuple'ının N'inci öğesini alır.

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| N | element index. |
| Args | tuple elements. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tuple | const [ValueTuple](../valuetuple/)\<Args...\>\& | öğeyi alınacak tuple. |

### Dönüş Değeri

N'inci tuple öğesinin değeri.

## İlgili

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Class [Index](../index/)
* Class [Range](../range/)
* Class [ValueTuple](../valuetuple/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)