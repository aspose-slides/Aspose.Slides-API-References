---
title: Convert()
second_title: Aspose.Slides için C++ API Referansı
description: RTTI bilgisi.
type: docs
weight: 1
url: /tr/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) metot


RTTI bilgisi.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | The object to be converted. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | The [System::TypeInfo](../../../system/typeinfo/) into which value is to be converted. |

### Dönüş Değeri

Dönüştürülmüş değer.
## Açıklamalar


Verilen [System::TypeInfo](../../../system/typeinfo/)'a bir değeri dönüştürür.
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) metot


Verilen [System::TypeCode](../../../system/typecode/)'a bir değeri dönüştürür.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | The object to be converted. |
| typeCode | [TypeCode](../../../system/typecode/) | The [System::TypeCode](../../../system/typecode/) into which value is to be converted. |

### Dönüş Değeri

Dönüştürülmüş değer.

## Ayrıca Bakınız

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IFormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)