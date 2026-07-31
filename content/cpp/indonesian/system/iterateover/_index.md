---
title: IterateOver()
second_title: Referensi API Aspose.Slides untuk C++
description: "Properti fungsi ini membungkus objek enumerable (atau iterable) sehingga dapat digunakan dengan perulangan berbasis rentang. Overload ini untuk Enumerable tanpa metode begin(), end() dengan argumen tipe target untuk (auto& value : IterateOver<SomeType>(enumerable))"
type: docs
weight: 2471
url: /id/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) function


Properti fungsi ini membungkus objek enumerable (atau iterable) sehingga dapat digunakan dengan perulangan berbasis rentang. Overload ini untuk Enumerable tanpa metode begin(), end() dengan argumen tipe target untuk (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe target, harus dikembalikan dari iterator |
| Enumerable | Tipe objek yang dibungkus |

## System::IterateOver(System::SmartPtr\<Enumerable\>) function


Properti fungsi ini membungkus objek enumerable (atau iterable) sehingga dapat digunakan dengan perulangan berbasis rentang. Overload ini untuk Enumerable tanpa metode begin(), end() dengan argumen tipe target default untuk (auto& value : IterateOver(enumerable)) yang analog dengan kode C# berikut foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Enumerable | Tipe objek yang dibungkus |

## System::IterateOver(System::SmartPtr\<Enumerable\>) function


Properti fungsi ini membungkus objek enumerable (atau iterable) sehingga dapat digunakan dengan perulangan berbasis rentang. Overload ini untuk Enumerable dengan metode begin(), end() dengan argumen tipe target default untuk (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Enumerable | Tipe objek yang dibungkus |

## System::IterateOver(System::SmartPtr\<Enumerable\>) function


Properti fungsi ini membungkus objek enumerable (atau iterable) sehingga dapat digunakan dengan perulangan berbasis rentang. Overload ini untuk Enumerable dengan metode begin(), end() dengan tipe target yang sama dengan value_type asli dari iterator.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Enumerable | Tipe objek yang dibungkus |
| T | Tipe target yang harus dikembalikan dari iterator |

## System::IterateOver(System::SmartPtr\<Enumerable\>) function


Properti fungsi ini membungkus objek enumerable (atau iterable) sehingga dapat digunakan dengan perulangan berbasis rentang. Overload ini untuk Enumerable dengan metode begin(), end() dengan tipe target berbeda dan value_type asli dari iterator.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Enumerable | Tipe objek yang dibungkus |
| T | Tipe target yang harus dikembalikan dari iterator |

## System::IterateOver(const Enumerable *) function


Properti fungsi ini membungkus objek enumerable (atau iterable) sehingga dapat digunakan dengan perulangan berbasis rentang. Overload ini untuk Enumerable ini dengan tipe target default.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Enumerable | Tipe objek yang dibungkus |

## System::IterateOver(const Enumerable *) function


Properti fungsi ini membungkus objek enumerable (atau iterable) sehingga dapat digunakan dengan perulangan berbasis rentang. Overload ini untuk Enumerable tanpa metode begin(), end() dengan argumen tipe target untuk (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe target, harus dikembalikan dari iterator |
| Enumerable | Tipe objek yang dibungkus |

## Lihat Juga

* Kelas [SmartPtr](../smartptr/)
* Struktur [IsSmartPtr](../issmartptr/)
* Namespace [System](../)
* Pustaka [Aspose.Slides](../../)