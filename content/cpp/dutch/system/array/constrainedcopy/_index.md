---
title: ConstrainedCopy()
second_title: Aspose.Slides voor C++ API Referentie
description: Kopieert een bereik van elementen van een System.Array beginnend bij de opgegeven bron.
type: docs
weight: 716
url: /nl/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) methode


Kopieert een bereik van elementen van een [System.Array](../) beginnend bij de opgegeven bron.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| SrcType | Type van elementen in bron-array |
| DstType | Type van elementen in doel-array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Bron-array |
| srcIndex | **int64_t** | [Index](../../index/) in de bron-array die het begin van het bereik van te kopiëren items aangeeft |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Doel-array |
| dstIndex | **int64_t** | [Index](../../index/) in de doel-array waar gekopieerde items moeten worden ingevoegd |
| count | **int64_t** | Het aantal elementen om te kopiëren |
## Opmerkingen


TIJDELIJKE RUWE IMPLEMENTATIE ZONDER ENIGE ONVOLLEDIGHEIDEN!
## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [Array](../)
* Naamruimte [System](../../)
* Library [Aspose.Slides](../../../)