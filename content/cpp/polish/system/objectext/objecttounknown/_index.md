---
title: ObjectToUnknown()
second_title: Aspose.Slides dla C++ — dokumentacja API
description: Konwertuje Object na nieznany typ, obsługując zarówno typ inteligentnego wskaźnika, jak i sytuacje z wartością bpxed.
type: docs
weight: 131
url: /pl/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) metoda

Konwertuje [Object](../../object/) na nieznany typ, obsługując zarówno typ inteligentnego wskaźnika, jak i sytuacje z wartością bpxed.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ, na który konwertować [Object](../../object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) do konwersji. |

### Wartość zwracana

Either unboxed value or converted pointer.

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) metoda

Konwertuje [Object](../../object/) na nieznany typ, obsługując zarówno typ inteligentnego wskaźnika, jak i sytuacje z wartością boxed.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ, na który konwertować [Object](../../object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) do konwersji. |

### Wartość zwracana

Either unboxed value or converted pointer.

## Zobacz także

* Klasa [SmartPtr](../../smartptr/)
* Klasa [Object](../../object/)
* Klasa [ObjectExt](../)
* Struktura [IsSmartPtr](../../issmartptr/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)