---
title: ObjectToUnknown()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar Object till en okänd typ och hanterar både smart pekartyp och inpackade värdesituationer.
type: docs
weight: 131
url: /sv/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) metod


Konverterar [Object](../../object/) till en okänd typ och hanterar både smart pekartyp och inpackade värdesituationer.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ att konvertera [Object](../../object/) till. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) att konvertera. |

### Returvärde

Antingen avpakade värde eller konverterad pekare.

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) metod


Konverterar [Object](../../object/) till en okänd typ och hanterar både smart pekartyp och inpackade värdesituationer.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ att konvertera [Object](../../object/) till. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) att konvertera. |

### Returvärde

Antingen avpakade värde eller konverterad pekare.

## Se även

* Klass [SmartPtr](../../smartptr/)
* Klass [Object](../../object/)
* Klass [ObjectExt](../)
* Struktur [IsSmartPtr](../../issmartptr/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)