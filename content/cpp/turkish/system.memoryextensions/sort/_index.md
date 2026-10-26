---
title: Sort()
second_title: Aspose.Slides for C++ API Referansı
description: Span'ı özel bir karşılaştırıcı kullanarak sıralar.
type: docs
weight: 339
url: /tr/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) function

Bir [Span](../../system/span/)'i özel bir karşılaştırıcı kullanarak sıralar.

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin türü |
| TComparer | Karşılaştırıcı nesnenin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Sıralanacak span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Öğe karşılaştırması için karşılaştırıcı nesnesine akıllı işaretçi |

## System::MemoryExtensions::Sort(Span\<T\>\&) function

Bir [Span](../../system/span/)'i varsayılan karşılaştırma kullanarak sıralar.

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Sıralanacak span |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) function

Anahtar-değer çiftlerini özel bir karşılaştırıcı kullanarak sıralar (anahtarlar ve değerler birlikte sıralanır)

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TKey | Anahtarların türü |
| TValue | Değerlerin türü |
| TComparer | Karşılaştırıcı nesnenin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Sıralanacak anahtarların span'i |
| values | [Span](../../system/span/)\<TValue\>\& | Sıralanacak değerlerin span'i (anahtarlarla eşleşmeyi koruyarak) |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Anahtar karşılaştırması için karşılaştırıcı nesnesine akıllı işaretçi |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) function

Anahtar-değer çiftlerini bir karşılaştırma temsilcisi kullanarak sıralar.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TKey | Anahtarların türü |
| TValue | Değerlerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Sıralanacak anahtarların span'i |
| values | [Span](../../system/span/)\<TValue\>\& | Sıralanacak değerlerin span'i |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) anahtar karşılaştırması için temsilci |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) function

Anahtar-değer çiftlerini varsayılan karşılaştırma kullanarak sıralar.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TKey | Anahtarların türü |
| TValue | Değerlerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Sıralanacak anahtarların span'i |
| values | [Span](../../system/span/)\<TValue\>\& | Sıralanacak değerlerin span'i |

## İlgili

* Typedef [SharedPtr](../../system/sharedptr/)
* Sınıf [Span](../../system/span/)
* Sınıf [Comparison](../../system/comparison/)
* Ad alanı [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)