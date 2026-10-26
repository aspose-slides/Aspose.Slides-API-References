---
title: ObjectToUnknown()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte Object in un tipo sconosciuto, gestendo sia il tipo puntatore intelligente sia le situazioni di valore impacchettato.
type: docs
weight: 131
url: /it/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) metodo

Converte [Object](../../object/) in un tipo sconosciuto, gestendo sia il tipo puntatore intelligente sia le situazioni di valore imballato.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo per convertire [Object](../../object/) in. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) da convertire. |

### Valore restituito

Restituisce il valore non impacchettato o il puntatore convertito.

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) metodo

Converte [Object](../../object/) in un tipo sconosciuto, gestendo sia il tipo puntatore intelligente sia le situazioni di valore impacchettato.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo per convertire [Object](../../object/) in. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) da convertire. |

### Valore restituito

Restituisce il valore non impacchettato o il puntatore convertito.

## Vedi anche

* Classe [SmartPtr](../../smartptr/)
* Classe [Object](../../object/)
* Classe [ObjectExt](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)