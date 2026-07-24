---
title: ConstrainedCopy()
second_title: Aspose.Slides für C++ API Referenz
description: Kopiert einen Bereich von Elementen aus einem System.Array, beginnend bei der angegebenen Quelle.
type: docs
weight: 716
url: /de/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) Methode


Kopiert einen Bereich von Elementen aus einem [System.Array](../) beginnend bei der angegebenen Quelle.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| SrcType | Typ der Elemente im Quellarray |
| DstType | Typ der Elemente im Zielarray |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Quellarray |
| srcIndex | **int64_t** | [Index](../../index/) im Quellarray, das den Beginn des zu kopierenden Bereichs bezeichnet |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Zielarray |
| dstIndex | **int64_t** | [Index](../../index/) im Zielarray, an dem die eingefügten Elemente beginnen |
| count | **int64_t** | Die Anzahl der zu kopierenden Elemente |

## Bemerkungen

TEMPORÄRE ROHE IMPLEMENTIERUNG OHNE IRGENDEINE UNDO-FUNKTION!

## Siehe Auch

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [Array](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)