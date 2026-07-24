---
title: LastIndexOf()
second_title: Aspose.Slides für C++ API Referenz
description: Bestimmt den Index des letzten Auftretens des angegebenen Elements in einem Bereich von Elementen des Arrays, der durch den Startindex und die Anzahl der Elemente im Bereich angegeben ist.
type: docs
weight: 703
url: /de/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) Methode

Bestimmt den Index des letzten Auftretens des angegebenen Elements in einem Bereich von Elementen des Arrays, der durch den Startindex und die Anzahl der Elemente im Bereich angegeben ist.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ArrayType | Typ der Elemente im Ziel-Array |
| ValueType | Typ des zu suchenden Elements im Array |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) zum Durchsuchen des angegebenen Elements |
| value | const [ValueType](../valuetype/)\& | Index des Elements, dessen Index ermittelt werden soll |
| startIndex | int | [Index](../../index/) bei dem die Suche gestartet wird |
| count | int | Anzahl der Elemente des zu durchsuchenden Bereichs |

### Rückgabewert

[Index](../../index/) des letzten Auftretens des angegebenen Elements, falls das Element gefunden wird, andernfalls -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) Methode

Bestimmt den Index des letzten Auftretens des angegebenen Elements im Array, beginnend beim angegebenen Index.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ArrayType | Typ der Elemente im Ziel-Array |
| ValueType | Typ des zu suchenden Elements im Array |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) zum Durchsuchen des angegebenen Elements |
| value | const [ValueType](../valuetype/)\& | Index des Elements, dessen Index ermittelt werden soll |
| startIndex | int | [Index](../../index/) bei dem die Suche gestartet wird |

### Rückgabewert

[Index](../../index/) des letzten Auftretens des angegebenen Elements, falls das Element gefunden wird, andernfalls -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) Methode

Bestimmt den Index des letzten Auftretens des angegebenen Elements im Array.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ArrayType | Typ der Elemente im Ziel-Array |
| ValueType | Typ des zu suchenden Elements im Array |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) zum Durchsuchen des angegebenen Elements |
| value | const [ValueType](../valuetype/)\& | Index des Elements, dessen Index ermittelt werden soll |

### Rückgabewert

[Index](../../index/) des letzten Auftretens des angegebenen Elements, falls das Element gefunden wird, andernfalls -1

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Klasse [Array](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)