---
title: ToType()
second_title: Aspose.Slides för C++ API-referens
description: "Konverterar värdet för detta objekt till ett System::Object av den angivna System::Type som har ett motsvarande värde, med hjälp av den angivna kulturspecifika formateringsinformationen."
type: docs
weight: 209
url: /sv/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) metod

Konverterar värdet för detta objekt till en [System::Object](../../object/) av den angivna System::Type som har ett motsvarande värde, med hjälp av den angivna kulturspecifika formateringsinformationen.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | System::Type som värdet för detta objekt konverteras till. |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | En [System::IFormatProvider](../../iformatprovider/)-implementering av ett gränssnitt som tillhandahåller kulturspecifik formateringsinformation. |

### Returvärde

En [System::Object](../../object/)-instans av typen conversionType vars värde är motsvarande värdet för detta objekt.

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Klass [Object](../../object/)
* Klass [TypeInfo](../../typeinfo/)
* Klass [IFormatProvider](../../iformatprovider/)
* Klass [IConvertible](../)
* Namnrymd [System](../../)
* Library [Aspose.Slides](../../../)