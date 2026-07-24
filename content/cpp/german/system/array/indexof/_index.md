---
title: IndexOf()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt den Index des ersten Auftretens des angegebenen Elements im Array.
type: docs
weight: 131
url: /de/system/array/indexof/
---
## Array::IndexOf(const T\&) const Methode

Bestimmt den Index des ersten Auftretens des angegebenen Elements im Array.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | const T\& | Index des Elements, dessen Index zu bestimmen ist |

### Rückgabewert

[Index](../../index/) des ersten Auftretens des angegebenen Elements, falls das Element gefunden wird, sonst -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) Methode

Bestimmt den Index des ersten Auftretens des angegebenen Elements im Array.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ArrayType | Typ der Elemente im Ziel-Array |
| ValueType | Typ des zu suchenden Elements im Array |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) zum Durchsuchen des angegebenen Elements in |
| value | const [ValueType](../valuetype/)\& | Index des Elements, dessen Index zu bestimmen ist |

### Rückgabewert

[Index](../../index/) des ersten Auftretens des angegebenen Elements, falls das Element gefunden wird, sonst -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) Methode

Bestimmt den Index des ersten Auftretens des angegebenen Elements im Array beginnend ab dem angegebenen Index.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ArrayType | Typ der Elemente im Ziel-Array |
| ValueType | Typ des zu suchenden Elements im Array |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) zum Durchsuchen des angegebenen Elements in |
| value | const [ValueType](../valuetype/)\& | Index des Elements, dessen Index zu bestimmen ist |
| startIndex | int | [Index](../../index/) bei dem die Suche gestartet wird |

### Rückgabewert

[Index](../../index/) des ersten Auftretens des angegebenen Elements, falls das Element gefunden wird, sonst -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) Methode

Bestimmt den Index des ersten Auftretens des angegebenen Elements in einem Bereich von Elementen des Arrays, der durch den Startindex und die Anzahl der Elemente im Bereich angegeben wird.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ArrayType | Typ der Elemente im Ziel-Array |
| ValueType | Typ des zu suchenden Elements im Array |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) zum Durchsuchen des angegebenen Elements in |
| value | const [ValueType](../valuetype/)\& | Index des Elements, dessen Index zu bestimmen ist |
| startIndex | int | [Index](../../index/) bei dem die Suche gestartet wird |
| count | int | Anzahl der Elemente des zu durchsuchenden Bereichs |

### Rückgabewert

[Index](../../index/) des ersten Auftretens des angegebenen Elements, falls das Element gefunden wird, sonst -1

## Siehe Auch

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Klasse [Array](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)