---
title: IterateOver()
second_title: Aspose.Slides for C++ API Referansı
description: "Bu işlev özelliği, enumerable (veya iterable) nesnesini sarar, böylece range-based for döngüsüyle kullanılabilir. Bu aşırı yükleme, begin(), end() metodları olmayan Enumerable için hedef tip argümanı ile (auto& value : IterateOver<SomeType>(enumerable)) şeklinde kullanılır."
type: docs
weight: 2471
url: /tr/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) fonksiyon

Bu işlev özelliği, enumerable (veya iterable) nesnesini sarar, böylece range-based for döngüsü ile kullanılabilir. Bu aşırı yükleme, begin(), end() metodları olmayan Enumerable için hedef tip argümanı ile (auto& value : IterateOver<SomeType>(enumerable)) şeklinde kullanılır.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip, iterator tarafından döndürülmelidir |
| Enumerable | Sarmalanan nesnenin tipi |

## System::IterateOver(System::SmartPtr\<Enumerable\>) fonksiyon

Bu işlev özelliği, enumerable (veya iterable) nesnesini sarar, böylece range-based for döngüsü ile kullanılabilir. Bu aşırı yükleme, begin(), end() metodları olmayan Enumerable için varsayılan hedef tip argümanı ile (auto& value : IterateOver(enumerable)) kullanılır; aşağıdaki C# koduna benzer şekilde foreach (var value in enumerable).

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Enumerable | Sarmalanan nesnenin tipi |

## System::IterateOver(System::SmartPtr\<Enumerable\>) fonksiyon

Bu işlev özelliği, enumerable (veya iterable) nesnesini sarar, böylece range-based for döngüsü ile kullanılabilir. Bu aşırı yükleme, begin(), end() metodları bulunan Enumerable için varsayılan hedef tip argümanı ile (auto& value : IterateOver(enumerable)) kullanılabilir.

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Enumerable | Sarmalanan nesnenin tipi |

## System::IterateOver(System::SmartPtr\<Enumerable\>) fonksiyon

Bu işlev özelliği, enumerable (veya iterable) nesnesini sarar, böylece range-based for döngüsü ile kullanılabilir. Bu aşırı yükleme, begin(), end() metodları bulunan Enumerable için iterator’un orijinal value_type’ı ile aynı hedef tipi kullanır.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Enumerable | Sarmalanan nesnenin tipi |
| T | Döndürülecek hedef tip |

## System::IterateOver(System::SmartPtr\<Enumerable\>) fonksiyon

Bu işlev özelliği, enumerable (veya iterable) nesnesini sarar, böylece range-based for döngüsü ile kullanılabilir. Bu aşırı yükleme, begin(), end() metodları bulunan Enumerable için farklı bir hedef tip ve iterator’un orijinal value_type’ı birlikte kullanır.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Enumerable | Sarmalanan nesnenin tipi |
| T | Döndürülecek hedef tip |

## System::IterateOver(const Enumerable *) fonksiyon

Bu işlev özelliği, enumerable (veya iterable) nesnesini sarar, böylece range-based for döngüsü ile kullanılabilir. Bu aşırı yükleme, const Enumerable* için varsayılan hedef tip kullanır.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Enumerable | Sarmalanan nesnenin tipi |

## System::IterateOver(const Enumerable *) fonksiyon

Bu işlev özelliği, enumerable (veya iterable) nesnesini sarar, böylece range-based for döngüsü ile kullanılabilir. Bu aşırı yükleme, begin(), end() metodları olmayan Enumerable için hedef tip argümanı ile (auto& value : IterateOver<SomeType>(enumerable)) kullanılabilir.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip, iterator tarafından döndürülmelidir |
| Enumerable | Sarmalanan nesnenin tipi |

## Bakınız

* Sınıf [SmartPtr](../smartptr/)
* Yapı [IsSmartPtr](../issmartptr/)
* İsimAlanı [System](../)
* Kütüphane [Aspose.Slides](../../)