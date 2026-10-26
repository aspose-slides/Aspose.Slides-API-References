---
title: ToObject()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen 64-bit işaretsiz tamsayı değerini bir enum üyesine dönüştürür.
type: docs
weight: 40
url: /tr/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) yöntemi

Belirtilen 64-bit işaretsiz tamsayı değerini bir enum üyesine dönüştürür.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Dönülecek enum type. |
| value | **uint64_t** | Enum üyesine dönüştürülecek value. |

### Dönüş Değeri

value değerine ayarlanmış enum örneği.

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) yöntemi

Belirtilen nesneyi bir tam sayı değeriyle bir enum üyesine dönüştürür.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Dönülecek enum type. |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Enum üyesine dönüştürülecek value. |

### Dönüş Değeri

value değeri value olan bir enum nesnesi.

## Bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [Object](../../object/)
* Sınıf [TypeInfo](../../typeinfo/)
* Sınıf [EnumValuesBase](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)