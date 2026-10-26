---
title: Parse()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací objekt, který představuje hodnotu konstanty výčtu zadaného typu výčtu se zadaným názvem.
type: docs
weight: 27
url: /cs/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) metoda


Vrací objekt, který představuje hodnotu konstanty výčtu zadaného typu výčtu se zadaným názvem.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) objekt představující typ hodnoty výčtu, který se má vrátit |
| str | const [String](../../string/)\& | Název konstanty výčtu |
| ignoreCase | **bool** | Určuje, zda se má při interpretaci názvu konstanty výčtu ignorovat velikost písmen |

### Návratová hodnota

Objekt představující hodnotu konstanty výčtu, jejíž název je určen v **str**.

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [String](../../string/)
* Class [EnumValuesBase](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)