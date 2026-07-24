---
title: SetValue()
second_title: Aspose.Slides for C++ API Referansı
description: Özellik değerini belirli bir nesneye ayarlar.
type: docs
weight: 14
url: /tr/system.reflection/propertyinfo/setvalue/
---
## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>) metod

Belirli bir nesneye özellik değerini ayarlar.

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) özelliği yazmak için. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Ayarlanacak özelliğin değeri. |

## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) metod

Belirli bir nesneye özellik değerini ayarlar.

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) özelliği yazmak için. |
| indexer | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Bunlar, indeksli özellikler için isteğe bağlı indeks değerleridir. İndekslenmemiş özellikler için bu değer null olmalıdır. |
| value | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | Ayarlanacak özelliğin değeri. |

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)