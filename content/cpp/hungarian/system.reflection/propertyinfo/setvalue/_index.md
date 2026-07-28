---
title: SetValue()
second_title: Aspose.Slides C++ API Referencia
description: Beállítja a tulajdonság értékét egy adott objektumra.
type: docs
weight: 14
url: /hu/system.reflection/propertyinfo/setvalue/
---
## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>) metódus


Beállítja a tulajdonság értékét egy adott objektumra.

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) a tulajdonság írásához. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | a beállítandó tulajdonság értéke. |

## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) metódus


Beállítja a tulajdonság értékét egy adott objektumra.

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) a tulajdonság írásához. |
| indexer | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Ezek opcionális index értékek indexelt tulajdonságokhoz. Nem indexelt tulajdonságok esetén ennek az értéknek nullának kell lennie. |
| value | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | a beállítandó tulajdonság értéke. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [Object](../../../system/object/)
* Osztály [PropertyInfo](../)
* Névtere [System::Reflection](../../)
* Library [Aspose.Slides](../../../)