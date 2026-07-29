---
title: Parse()
second_title: Aspose.Slides för C++ API-referens
description: Paketerar värdet av en uppräkningskonstant för den angivna uppräkningen med det angivna namnet. En parameter anger om versaler ska ignoreras vid tolkning av strängen som representerar namnet på uppräkningskonstanten.
type: docs
weight: 53
url: /sv/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) method


Paketerar värdet av en uppräkningskonstant för den angivna uppräkningen med det angivna namnet. En parameter anger om versaler bör ignoreras vid tolkning av strängen som specificerar namnet på uppräkningskonstanten.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Anger typen av uppräkningen |
| str | const [String](../../string/)\& | Namnet på uppräkningskonstanten vars värde ska paketeras |
| ignoreCase | **bool** | Anger om versaler ska ignoreras vid tolkning av strängen som representerar namnet på uppräkningskonstanten |

### Returvärde

En delad pekare till objektet som representerar det paketerade värdet av den angivna uppräkningskonstanten

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) method


Paketerar värdet av en uppräkningskonstant för den angivna uppräkningen med det angivna namnet.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Anger typen av uppräkningen |
| str | const [String](../../string/)\& | Namnet på uppräkningskonstanten vars värde ska paketeras |

### Returvärde

En delad pekare till objektet som representerar det paketerade värdet av den angivna uppräkningskonstanten

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [String](../../string/)
* Class [BoxedValueBase](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)