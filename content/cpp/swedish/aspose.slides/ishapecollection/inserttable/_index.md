---
title: InsertTable()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny tabell och infogar den i shape collection på det angivna indexet.
type: docs
weight: 443
url: /sv/aspose.slides/ishapecollection/inserttable/
---
## IShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) metod


Skapar en ny tabell och infogar den i shape collection på det angivna indexet.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där tabellen ska infogas. |
| x | **float** | X-koordinaten för tabellen, i punkter. |
| y | **float** | Y-koordinaten för tabellen, i punkter. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | En array av double som representerar bredden på tabellens kolumner, i punkter. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | En array av double som representerar höjden på tabellens rader, i punkter. |

### Returvärde

Det nyss skapade [ITable](../../itable/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [ITable](../../itable/)
* Klass [IShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)