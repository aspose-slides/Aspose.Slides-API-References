---
title: Format()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací řetězcovou reprezentaci hodnoty reprezentované aktuálním objektem pomocí zadaného formátu.
type: docs
weight: 1
url: /cs/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) method

Vrací řetězcovou reprezentaci hodnoty reprezentované aktuálním objektem pomocí zadaného formátu.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| format | [System::String](../../string/) | Řetězcový formát |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | Objekt k naformátování |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Objekt poskytující informace o formátování |

### Návratová hodnota

Řetězcová reprezentace **arg** naformátovaná podle formátu určeného **format** a **formatProvider**.

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [Object](../../object/)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [ICustomFormatter](../)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)