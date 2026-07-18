---
title: Convert()
second_title: Aspose.Slides για C++ Αναφορά API
description: Πληροφορίες RTTI.
type: docs
weight: 1
url: /el/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) μέθοδος

Πληροφορίες RTTI.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Το αντικείμενο που θα μετατραπεί. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Το [System::TypeInfo](../../../system/typeinfo/) στο οποίο η τιμή θα μετατραπεί. |

### Τιμή Επιστροφής

Η μετατρεπόμενη τιμή.
## Παρατηρήσεις

Μετατρέπει μια τιμή στο δοσμένο [System::TypeInfo](../../../system/typeinfo/). 
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) μέθοδος

Μετατρέπει μια τιμή στο δοσμένο [System::TypeCode](../../../system/typecode/).

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Το αντικείμενο που θα μετατραπεί. |
| typeCode | [TypeCode](../../../system/typecode/) | Το [System::TypeCode](../../../system/typecode/) στο οποίο η τιμή θα μετατραπεί. |

### Τιμή Επιστροφής

Η μετατρεπόμενη τιμή.

## Δείτε επίσης

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [TypeInfo](../../../system/typeinfo/)
* Κλάση [IFormatterConverter](../)
* Χώρος ονομάτων [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)