---
title: Index
second_title: Aspose.Slides for C++ API Referansı
description: "Bir koleksiyondaki bir indeksi temsil eder. Indeks, başlangıçtan veya sondan olabilir. Bu tip yığıt üzerinde tahsis edilmeli ve fonksiyonlara değer olarak ya da referansla aktarılmalıdır. Bu tipin nesnelerini yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 1015
url: /tr/system/index/
---
## Index sınıfı


Bir koleksiyona ait bir indeksi temsil eder. Indeks, başlangıçtan veya sondan olabilir. Bu tip yığıt üzerinde tahsis edilmeli ve fonksiyonlara değer olarak ya da referansla aktarılmalıdır. Bu tipin nesnelerini yönetmek için [System::SmartPtr](../smartptr/) sınıfını asla kullanmayın.

```cpp
class Index : public System::Details::BoxableObjectBase
```

## Yöntemler

| Metod | Açıklama |
| --- | --- |
| **bool** [Equals](./equals/)(const [Index](./)\&) const | Geçerli örnek ile belirtilen [Index](./)'nin aynı konumu temsil edip etmediğini belirler. |
| static constexpr [Index](./) [FromEnd](./fromend/)(**int32_t**) | Koleksiyonun sonuna göreceli bir [Index](./) oluşturur. |
| static constexpr [Index](./) [get_End](./get_end/)() | Bir koleksiyonun sonunu temsil eden [Index](./) nesnesini alır. |
| constexpr **bool** [get_IsFromEnd](./get_isfromend/)() const | İndeksin sondan olup olmadığını gösteren bir değer alır. |
| static constexpr [Index](./) [get_Start](./get_start/)() | Bir koleksiyonun başlangıcını temsil eden [Index](./) nesnesini alır. |
| constexpr **int32_t** [get_Value](./get_value/)() const | İndeks değerini alır. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Geçerli indeks için bir hash kodu döndürür. |
| **int32_t** [GetOffset](./getoffset/)(**int32_t**) const | Geçerli [Index](./)'yi belirtilen uzunluktaki bir koleksiyonun başlangıcından ofsete dönüştürür. |
| constexpr [Index](./index/)() | Bir koleksiyonun başlangıcını temsil eden bir örnek oluşturur. |
| constexpr [Index](./index/)(**int32_t**) | Koleksiyonun başlangıcından belirtilen konumu temsil eden bir örnek oluşturur. |
| constexpr [Index](./index/)(**int32_t**, **bool**) | Belirtilen indeksi temsil eden bir örnek oluşturur. |
## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)