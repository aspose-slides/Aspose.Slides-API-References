---
title: Parse()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett objekt som representerar ett värde av en uppräkningskonstant av den angivna uppräknings-typen med det angivna namnet.
type: docs
weight: 27
url: /sv/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) metod


Returnerar ett objekt som representerar ett värde av en uppräkningskonstant av den angivna uppräknings-typen med det angivna namnet.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Objektet [TypeInfo](../../typeinfo/) som representerar typen av uppräkningsvärdet som ska returneras |
| str | const [String](../../string/)\& | Namnet på uppräkningskonstanten |
| ignoreCase | **bool** | Specificerar om skiftläget ska ignoreras när namnet på uppräkningskonstanten tolkas |

### Returvärde

Ett objekt som representerar värdet av uppräkningskonstanten vars namn anges i **str**.

## Se även

* Typdefinition [SharedPtr](../../sharedptr/)
* Klass [Object](../../object/)
* Klass [TypeInfo](../../typeinfo/)
* Klass [String](../../string/)
* Klass [EnumValuesBase](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)