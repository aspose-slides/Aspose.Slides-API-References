---
title: set_ShowValue()
second_title: อ้างอิง API ของ Aspose.Slides for C++
description: อธิบายพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ ค่าจริงจะแสดงค่าร้อยละ ค่าปลอมจะซ่อน เขียน bool.
type: docs
weight: 131
url: /th/aspose.slides.charts/idatalabelformat/set_showvalue/
---
## IDataLabelFormat::set_ShowValue(bool) เมธอด

Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Write **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowValue(bool value)=0
```

## หมายเหตุ

If parent of this [DataLabelFormat](../../datalabelformat/) object is a [DataLabelCollection](../../datalabelcollection/) collection of data labels then this property gets or sets the default value of the ShowValue property for the new data labels in the [DataLabelCollection](../../datalabelcollection/) collection. Set this property with value also sets this value to the ShowValue property for all data labels in the [DataLabelCollection](../../datalabelcollection/) collection (i.e. \"DataLabels.DefaultDataLabelFormat.ShowValue = val;\" cause to all DataLabels[i].ShowValue is equal to val). 

## ดูเพิ่มเติม

* คลาส [IDataLabelFormat](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)