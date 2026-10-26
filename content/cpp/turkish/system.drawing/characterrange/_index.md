---
title: CharacterRange
second_title: Aspose.Slides for C++ API Referansı
description: "Bir dizedeki karakter konumlarının aralığını temsil eder. Bu tip yığıt üzerinde allocate edilmeli ve fonksiyonlara değer ya da referans olarak geçirilmelidir. Bu tipin nesnelerini yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 40
url: /tr/system.drawing/characterrange/
---
## CharacterRange sınıfı


Bir dizedeki karakter konumlarının aralığını temsil eder. Bu tip yığıt üzerinde allocate edilmeli ve fonksiyonlara değer ya da referans olarak geçirilmelidir. [System::SmartPtr](../../system/smartptr/) sınıfını bu tipin nesnelerini yönetmek için asla kullanmayın.

```cpp
class CharacterRange
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  [CharacterRange](./characterrange/)(**int32_t**, **int32_t**) | Belirtilen aralığı temsil eden [CharacterRange](./) sınıfının yeni bir örneğini oluşturur. |
|  [CharacterRange](./characterrange/)() | Boş bir aralığı temsil eden [CharacterRange](./) sınıfının yeni bir örneğini oluşturur. |
| **int32_t** [get_First](./get_first/)() const | Geçerli nesne tarafından temsil edilen aralığın ilk karakterinin konumunu döndürür. |
| **int32_t** [get_Length](./get_length/)() const | Geçerli nesne tarafından temsil edilen aralığın karakter sayısını döndürür. |
| **bool** [operator!=](./operator_not_equal/)(const [CharacterRange](./)\&) const | Geçerli ve belirtilen nesnelerin farklı aralıkları temsil edip etmediğini belirler. |
| **bool** [operator==](./operator_equal_equal/)(const [CharacterRange](./)\&) const | Geçerli ve belirtilen nesnelerin aynı aralığı temsil edip etmediğini belirler. |
| void [set_First](./set_first/)(**int32_t**) | Geçerli nesne tarafından temsil edilen aralığın ilk karakterinin konumunu ayarlar. |
| void [set_Length](./set_length/)(**int32_t**) | Geçerli nesne tarafından temsil edilen aralığın karakter sayısını döndürür. |
## Ayrıca Bakınız

* Namespace [System::Drawing](../)
* Kütüphane [Aspose.Slides](../../)