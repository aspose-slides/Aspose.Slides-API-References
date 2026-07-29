---
title: UnknownToObject()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar okänd typ till Object, hanterar både smartpekar-typ och värdetyp.
type: docs
weight: 118
url: /sv/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) metod


Konverterar okänd typ till [Object](../../object/), hanterar både smartpekar-typ och värdetyp.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ att konvertera till [Object](../../object/). |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | T | [Object](../../object/) att konvertera. |

### Returvärde

Smart pekare till [Object](../../object/) som är antingen en konverterad pekare eller ett inkapslat värde.

## ObjectExt::UnknownToObject(const T\&) metod


Konverterar okänd typ till [Object](../../object/), hanterar både smartpekar-typ och värdetyp.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ att konvertera till [Object](../../object/). |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) att konvertera. |

### Returvärde

Smart pekare till [Object](../../object/) som är antingen en konverterad pekare eller ett inkapslat värde.

## Se även

* Klass [SmartPtr](../../smartptr/)
* Klass [Object](../../object/)
* Klass [ObjectExt](../)
* Struktur [IsSmartPtr](../../issmartptr/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)