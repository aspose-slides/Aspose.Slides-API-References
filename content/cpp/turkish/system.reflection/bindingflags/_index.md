---
title: BindingFlags
second_title: Aspose.Slides için C++ API Referansı
description: Üyeleri ve tip arama modlarını ve bağlamaları tanımlar.
type: docs
weight: 157
url: /tr/system.reflection/bindingflags/
---
## BindingFlags enum

Üyeleri ve tip arama modlarını ve bağlamaları tanımlar.

```cpp
enum class BindingFlags
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Default | 0 | Özel bir seçenek yok. |
| IgnoreCase | 1 | Öğeyi ararken adın büyük/küçük harf duyarlılığını yoksayar. |
| DeclaredOnly | 2 | Sadece tip içinde bildirilen üyeleri ve temel tiplerdeki olmayanları arar. |
| Instance | 4 | Örnek üyeleri tarar. |
| Static | 8 | Statik üyeleri tarar. |
| Public | 16 | Public üyeleri tarar. |
| NonPublic | 32 | Non-public üyeleri tarar. |
| FlattenHierarchy | 64 | Temel tipin public ve protected statik üyelerini tarar. |
| InvokeMethod | 256 | Metodu çağırır. |
| CreateInstance | 512 | Yansıtılan tipin örneğini oluşturur. |
| GetField | 1024 | Alan değerini alır. |
| SetField | 2048 | Alan değerini ayarlar. |
| GetProperty | 4096 | Özellik değerini alır. |
| SetProperty | 8192 | Özellik değerini ayarlar. |
| PutDispProperty | 16384 | COM özelliğini ayarlar. |
| PutRefDispProperty | 32768 | COM referans özelliğini ayarlar. |
| ExactBinding | 65536 | Tip bağlamı tam olmalı, herhangi bir tip değişikliği olmadan. |
| SuppressChangeType | 131072 | Desteklenmiyor. |
| OptionalParamBinding | 262144 | Argüman sayısına göre aşırı yüklemeyi seçer. |
| IgnoreReturn | 16777216 | COM interop dönüş değerini yoksayar. |

## Ayrıca Bakınız

* Ad alanı [System::Reflection](../)
* Kütüphane [Aspose.Slides](../../)