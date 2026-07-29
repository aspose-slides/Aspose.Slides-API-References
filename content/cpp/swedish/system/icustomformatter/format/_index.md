---
title: Format()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en strängrepresentation av ett värde som representeras av det aktuella objektet med hjälp av det angivna formatet.
type: docs
weight: 1
url: /sv/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) metod

Returnerar en strängrepresentation av ett värde som representeras av det aktuella objektet med hjälp av det angivna formatet.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | [System::String](../../string/) | Strängformatet |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | Objektet som ska formateras |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Objektet som tillhandahåller formateringsinformationen |

### Returvärde

Strängrepresentationen av **arg** formaterad enligt formatet som specificeras av **format** och **formatProvider**

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../../string/)
* Klass [Object](../../object/)
* Klass [IFormatProvider](../../iformatprovider/)
* Klass [ICustomFormatter](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)