---
title: Ref()
second_title: Aspose.Slides for C++ API Referansı
description: DynamicWeakPtr nesnesine referans oluşturur. Çevirmen tarafından fonksiyon argümanları referans yoluyla geçilirken kullanılır.
type: docs
weight: 2458
url: /tr/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) fonksiyonu


[DynamicWeakPtr](../dynamicweakptr/) nesnesine referans oluşturur. Çevirmen tarafından fonksiyon argümanları referans yoluyla geçilirken kullanılır.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```


### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | İşaret edilen tip. |
| trunkMode | Akıllı göstericinin kendisinin modu. |
| weakLeafs | SetTemplateWeakPtr metodunun çağrılması gereken şablon argümanlarının indeksleri. |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | Referans oluşturulacak akıllı gösterici. |

### Dönüş Değeri

Akıllı gösterici referansı.

## System::Ref(T\&) fonksiyonu


Nesnelere referans edinmek için yardımcı fonksiyon. [System::DynamicWeakPtr](../dynamicweakptr/)'un atamalardan sonra referans verilen nesneyi güncellemesini sağlamak için kullanılır.

```cpp
template<typename T> T & System::Ref(T &value)
```


### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | Referans oluşturulacak tip. |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| value | T\& | Referans oluşturulacak değer. |

### Dönüş Değeri

Bu fonksiyona geçirilen değere referans.

## Ayrıca Bakınız

* Sınıf [DynamicWeakPtr](../dynamicweakptr/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)