---
title: ConstrainedCopy()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Kopíruje rozsah prvků ze System.Array počínaje určeným zdrojem.
type: docs
weight: 716
url: /cs/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method


Kopíruje rozsah prvků z [System.Array](../) počínaje určeným zdrojem.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| SrcType | Type of elements in source array |
| DstType | Type of elements in destination array |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Source array |
| srcIndex | **int64_t** | [Index](../../index/) v zdrojovém poli určující začátek rozsahu položek ke kopírování |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Destination array |
| dstIndex | **int64_t** | [Index](../../index/) v cílovém poli, kde začít vkládat zkopírované položky |
| count | **int64_t** | The number of elements to copy |
## Poznámky


DOČASNÁ SYROVÁ IMPLEMENTACE BEZ JAKÉKOLI OPRAV! 
## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Třída [Array](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)