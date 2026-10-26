---
title: Format()
second_title: Aspose.Slides C++ API Referencia
description: Visszaadja a megadott formátumot használva a jelenlegi objektum által képviselt érték karakterlánc ábrázolását.
type: docs
weight: 1
url: /hu/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) metódus


A megadott formátumot használva visszaadja az aktuális objektum által képviselt érték karakterlánc ábrázolását.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | [System::String](../../string/) | A karakterlánc formátuma |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | A formázandó objektum |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Az információt biztosító formázó objektum |

### Visszatérési érték

A **arg** karakterlánc ábrázolása, amely a **format** és **formatProvider** által megadott formátum szerint van formázva

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [Object](../../object/)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [ICustomFormatter](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)