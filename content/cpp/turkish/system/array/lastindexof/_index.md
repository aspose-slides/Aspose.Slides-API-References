---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen öğenin, başlangıç indeksi ve aralıktaki öğe sayısı ile belirlenen dizi öğeleri aralığında son kez göründüğü konumun dizinini belirler.
type: docs
weight: 703
url: /tr/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) metodu


Belirtilen öğenin son kez göründüğü konumun dizinini, başlangıç indeksi ve aralıktaki öğe sayısı ile belirlenen dizi aralığında belirler.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```


### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| ArrayType | Hedef dizinin öğe türü |
| ValueType | Dizide aranacak öğenin türü |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) içinde aranacak öğe |
| value | const [ValueType](../valuetype/)\& | Belirlenmesi gereken öğe indeksi |
| startIndex | int | [Index](../../index/) aramanın başladığı konum |
| count | int | Aranacak aralığın öğe sayısı |

### Dönüş Değeri

[Index](../../index/) belirtilen öğenin son oluşumunun değeri; öğe bulunursa, aksi takdirde -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) metodu


Belirtilen öğenin son kez göründüğü konumun dizinini, belirtilen indeksden başlayarak dizide belirler.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```


### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| ArrayType | Hedef dizinin öğe türü |
| ValueType | Dizide aranacak öğenin türü |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) içinde aranacak öğe |
| value | const [ValueType](../valuetype/)\& | Belirlenmesi gereken öğe indeksi |
| startIndex | int | [Index](../../index/) aramanın başladığı konum |

### Dönüş Değeri

[Index](../../index/) belirtilen öğenin son oluşumunun değeri; öğe bulunursa, aksi takdirde -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) metodu


Belirtilen öğenin son kez göründüğü konumun dizinini, dizide belirler.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```


### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| ArrayType | Hedef dizinin öğe türü |
| ValueType | Dizide aranacak öğenin türü |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) içinde aranacak öğe |
| value | const [ValueType](../valuetype/)\& | Belirlenmesi gereken öğe indeksi |

### Dönüş Değeri

[Index](../../index/) belirtilen öğenin son oluşumunun değeri; öğe bulunursa, aksi takdirde -1

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)