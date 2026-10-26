---
title: SetValue()
second_title: Riferimento API Aspose.Slides per C++
description: Imposta il valore della proprietà su un oggetto specifico.
type: docs
weight: 14
url: /it/system.reflection/propertyinfo/setvalue/
---
## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>) metodo


Imposta il valore della proprietà su un oggetto specifico.

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) per scrivere la proprietà su. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Valore della proprietà da impostare. |

## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) metodo


Imposta il valore della proprietà su un oggetto specifico.

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) per scrivere la proprietà su. |
| indexer | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Questi sono valori indice opzionali per le proprietà indicizzate. Per le proprietà non indicizzate, questo valore dovrebbe essere null. |
| value | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | Valore della proprietà da impostare. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Object](../../../system/object/)
* Classe [PropertyInfo](../)
* Spazio dei nomi [System::Reflection](../../)
* Library [Aspose.Slides](../../../)