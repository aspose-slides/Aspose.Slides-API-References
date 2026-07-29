---
title: AddTable()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny tabell och lägger till den i slutet av formsamlingen.
type: docs
weight: 430
url: /sv/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) metod


Skapar en ny tabell och lägger till den i slutet av formsamlingen.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | X-koordinaten för tabellen, i punkter. |
| y | **float** | Y-koordinaten för tabellen, i punkter. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | En array av double-värden som representerar bredden på tabellens kolumner, i punkter. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | En array av double-värden som representerar höjden på tabellens rader, i punkter. |

### Returvärde

Den nyss skapade [ITable](../../itable/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [ITable](../../itable/)
* Klass [IShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)