---
title: GetValue()
second_title: Aspose.Slides for C++ API Referansı
description: Belirli bir nesneden özelliğin değerini alır.
type: docs
weight: 1
url: /tr/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) yöntemi

Belirli bir nesneden özelliğin değerini alır.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) özelliği okunacak nesne. |

### Dönüş Değeri

Belirtilen nesne için belirtilen özelliğin değeri.

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) yöntemi

Belirli bir nesneden özelliğin değerini alır.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) özelliği okunacak nesne. |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | Bu değer indeksli özellikler için isteğe bağlı indeks değerleridir. İndekslenmemiş özellikler için bu değer null olmalıdır. |

### Dönüş Değeri

Belirtilen nesne için belirtilen özelliğin değeri.

## Başvurular

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [PropertyInfo](../)
* Ad alanı [System::Reflection](../../)
* Kütüphane [Aspose.Slides](../../../)