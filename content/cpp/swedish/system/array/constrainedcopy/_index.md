---
title: ConstrainedCopy()
second_title: Aspose.Slides för C++ API-referens
description: Kopierar ett intervall av element från en System.Array med start vid den angivna källan.
type: docs
weight: 716
url: /sv/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) metod


Kopierar ett intervall av element från en [System.Array](../) med start vid den angivna källan.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| SrcType | Typ av element i källarray |
| DstType | Typ av element i destinationsarray |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Källarray |
| srcIndex | **int64_t** | [Index](../../index/) i källarray som anger början av intervallet av objekt som ska kopieras |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Destinationsarray |
| dstIndex | **int64_t** | [Index](../../index/) i destinationsarray där kopierade objekt ska börja infogas |
| count | **int64_t** | Antalet element att kopiera |
## Anmärkningar

TILLFÄLLIG RÅ IMPLEMENTERING UTAN NÅGRA OAVSLUTADE!
## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Klass [Array](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)