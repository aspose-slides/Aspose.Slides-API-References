---
title: Convert()
second_title: Aspose.Slides C++ API Referansı
description: "Bir değeri verilen System::TypeInfo tipine dönüştürür."
type: docs
weight: 1
url: /tr/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) method

Verilen [System::TypeInfo](../../../system/typeinfo/)'ye bir değeri dönüştürür.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dönüştürülecek nesne. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Değerin dönüştürüleceği [System::TypeInfo](../../../system/typeinfo/). |

### Dönüş Değeri

Dönüştürülmüş değer.

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) method

Verilen [System::TypeCode](../../../system/typecode/)'ye bir değeri dönüştürür.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dönüştürülecek nesne. |
| typeCode | [TypeCode](../../../system/typecode/) | Değerin dönüştürüleceği [System::TypeCode](../../../system/typecode/). |

### Dönüş Değeri

Dönüştürülmüş değer.

## Diğer Bağlantılar

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [FormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)