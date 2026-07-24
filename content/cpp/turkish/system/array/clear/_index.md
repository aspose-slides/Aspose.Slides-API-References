---
title: Clear()
second_title: Aspose.Slides for C++ API Referansı
description: Mevcut nesne tarafından temsil edilen dizi salt okunur olduğu için desteklenmiyor.
type: docs
weight: 53
url: /tr/system/array/clear/
---
## Array::Clear() metodu


Not supported because the array represented by the current object is read-only.

```cpp
virtual void System::Array<T>::Clear() override
```


## Array::Clear(const ArrayPtr\<Type\>\&, int, int) metodu


Replaces **count** values starting at the **startIndex** index in the specified array with default values.

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Type | Hedef dizideki öğelerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Hedef dizi |
| startIndex | int | [Index](../../index/) öğeleri değiştirmeye başlanacak indeks |
| count | int | Değiştirilecek öğelerin sayısı |

## İlgili

* Typedef [ArrayPtr](../../arrayptr/)
* Metot [Type](../../object/type/)
* Sınıf [Array](../)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)