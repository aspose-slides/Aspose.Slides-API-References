---
title: ConstrainedCopy()
second_title: Aspose.Slides for C++ API Referencia
description: Másol egy elemtartományt egy System.Array-ból a megadott forrástól kezdve.
type: docs
weight: 716
url: /hu/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method


Másol egy elemtartományt egy [System.Array](../)-ból, a megadott forrástól kezdve.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| SrcType | A forrás tömb elemeinek típusa |
| DstType | A cél tömb elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Forrás tömb |
| srcIndex | **int64_t** | [Index](../../index/) a forrás tömbben, amely a másolandó elemtartomány kezdetét jelöli |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Cél tömb |
| dstIndex | **int64_t** | [Index](../../index/) a cél tömbben, ahol a másolt elemek beszúrását elkezdi |
| count | **int64_t** | A másolandó elemek száma |
## Megjegyzések


IDEIGLENES NYERS IMPLEMENTÁCIÓ NINCSEN HIBÁK! 
## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Osztály [Array](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)