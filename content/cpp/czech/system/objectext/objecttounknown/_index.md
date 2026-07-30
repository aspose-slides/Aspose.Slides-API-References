---
title: ObjectToUnknown()
second_title: Aspose.Slides pro C++ – reference API
description: Převádí Object na neznámý typ, řeší jak typ chytrého ukazatele, tak i situace se zabalenou hodnotou.
type: docs
weight: 131
url: /cs/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) metoda


Převádí [Object](../../object/) na neznámý typ, řeší jak typ chytrého ukazatele, tak i situace se zabalenou hodnotou.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ, na který se má převést [Object](../../object/). |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) k převodu. |

### Návratová hodnota

Buď nebalená hodnota nebo převedený ukazatel.

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) metoda


Převádí [Object](../../object/) na neznámý typ, řeší jak typ chytrého ukazatele, tak i situace se zabalenou hodnotou.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ, na který se má převést [Object](../../object/). |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) k převodu. |

### Návratová hodnota

Buď nebalená hodnota nebo převedený ukazatel.

## Viz také

* Třída [SmartPtr](../../smartptr/)
* Třída [Object](../../object/)
* Třída [ObjectExt](../)
* Struktura [IsSmartPtr](../../issmartptr/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)