---
title: GetValue()
second_title: Aspose.Slides C++ API referencia
description: Lekéri a property értékét egy adott objektumból.
type: docs
weight: 1
url: /hu/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) metódus


Lekéri a property értékét egy adott objektumból.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) a property olvasásához. |

### Visszatérési érték

A megadott property értéke a megadott objektumhoz.

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) metódus


Lekéri a property értékét egy adott objektumból.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) a property olvasásához. |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | Ezek opcionális indexértékek indexelt property-khez. Nem indexelt property-k esetén ennek az értéknek null értékűnek kell lennie. |

### Visszatérési érték

A megadott property értéke a megadott objektumhoz.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [Object](../../../system/object/)
* Osztály [PropertyInfo](../)
* Névtere [System::Reflection](../../)
* Könyvtár [Aspose.Slides](../../../)