---
title: UnboxToNullable()
second_title: Aspose.Slides C++ için API Referansı
description: Nesneyi nullable türe çözer.
type: docs
weight: 79
url: /tr/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) metot


Nesneyi nullable türe çözer.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) çözmek için. |
| safe | **bool** | Doğruysa, hatada nullptr döndür, aksi takdirde InvalidCastException fırlat. |

### Dönüş Değeri

Çözümlenmiş nullable değer (null olabilir).

## Ayrıca Bakınız

* Sınıf [Nullable](../../nullable/)
* Sınıf [SmartPtr](../../smartptr/)
* Sınıf [Object](../../object/)
* Sınıf [ObjectExt](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)