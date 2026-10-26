---
title: ToType()
second_title: Aspose.Slides pro C++ referenční příručka API
description: "Převede hodnotu této instance na System::Object zadaného System::Type, který má ekvivalentní hodnotu, pomocí zadaných kulturálně specifických informací o formátování."
type: docs
weight: 209
url: /cs/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) metoda


Převede hodnotu této instance na [System::Object](../../object/) zadaného System::Type, který má ekvivalentní hodnotu, pomocí zadaných kulturálně specifických informací o formátování.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | System::Type, na který je hodnota této instance převedena. |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | [System::IFormatProvider](../../iformatprovider/) implementace rozhraní, která poskytuje kulturálně specifické informace o formátování. |

### Návratová hodnota

[System::Object](../../object/) instance typu conversionType, jejíž hodnota je ekvivalentní hodnotě této instance.

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [Object](../../object/)
* Třída [TypeInfo](../../typeinfo/)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [IConvertible](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)