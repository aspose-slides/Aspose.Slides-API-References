---
title: UnknownToObject()
second_title: Aspose.Slides pro C++ API Referenci
description: Převádí neznámý typ na Object, a ošetřuje jak situace s typem inteligentního ukazatele, tak s typem hodnoty.
type: docs
weight: 118
url: /cs/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) metoda

Převádí neznámý typ na [Object](../../object/) a ošetřuje jak situace s typem inteligentního ukazatele, tak s typem hodnoty.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ, který se má převést na [Object](../../object/). |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | T | [Object](../../object/) k převodu. |

### Návratová hodnota

Inteligentní ukazatel na [Object](../../object/), který je buď převedený ukazatel nebo zabalená hodnota.

## ObjectExt::UnknownToObject(const T\&) metoda

Převádí neznámý typ na [Object](../../object/) a ošetřuje jak situace s typem inteligentního ukazatele, tak s typem hodnoty.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ, který se má převést na [Object](../../object/). |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) k převodu. |

### Návratová hodnota

Inteligentní ukazatel na [Object](../../object/), který je buď převedený ukazatel nebo zabalená hodnota.

## Viz také

* Třída [SmartPtr](../../smartptr/)
* Třída [Object](../../object/)
* Třída [ObjectExt](../)
* Struktura [IsSmartPtr](../../issmartptr/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)