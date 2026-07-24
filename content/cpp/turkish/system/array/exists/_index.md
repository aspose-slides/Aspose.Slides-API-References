---
title: Exists()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen Array nesnesinin, belirtilen koşulu karşılayan bir öğe içerip içermediğini belirler.
type: docs
weight: 781
url: /tr/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::function\<bool(T)>) metod

Belirtilen [Array](../) nesnesinin, belirtilen koşulu karşılayan bir öğe içerip içermediğini belirler.

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Öğeyi aranacak dizi |
| match | std::function\<**bool**(T)> | Gereksinimleri tanımlayan ve bir öğenin bunları karşılayıp karşılamadığını kontrol eden fonksiyon nesnesi |

### Dönüş Değeri

**arr** içinde **match** tarafından tanımlanan gereksinimleri karşılayan bir öğe varsa **True**

## Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Sınıf [Array](../)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)