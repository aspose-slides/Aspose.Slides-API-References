---
title: GetValue()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene il valore della proprietà da un oggetto specifico.
type: docs
weight: 1
url: /it/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) metodo

Ottiene il valore della proprietà da un oggetto specifico.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) da cui leggere la proprietà. |

### Valore di ritorno

Valore della proprietà specificata per l'oggetto specificato.

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) metodo

Ottiene il valore della proprietà da un oggetto specifico.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) da cui leggere la proprietà. |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | Questi sono valori di indice opzionali per le proprietà indicizzate. Per le proprietà non indicizzate, questo valore dovrebbe essere null. |

### Valore di ritorno

Valore della proprietà specificata per l'oggetto specificato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Object](../../../system/object/)
* Classe [PropertyInfo](../)
* Spazio dei nomi [System::Reflection](../../)
* Libreria [Aspose.Slides](../../../)