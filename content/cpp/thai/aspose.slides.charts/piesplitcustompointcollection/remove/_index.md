---
title: Remove()
second_title: อ้างอิง API ของ Aspose.Slides for C++ 
description: ลบรายการออกจากคอลเลกชัน.
type: docs
weight: 79
url: /th/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) เมธอด


ลบรายการออกจากคอลเลกชัน.

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | จุดข้อมูลที่จะลบ. |

### ค่าที่ส่งคืน

true หากรายการถูกลบสำเร็จ; มิฉะนั้น false. เมธอดนี้ยังส่งคืน false หากไม่พบรายการใน [System::Collections::Generic::List](../../../system.collections.generic/list/){T}.

## PieSplitCustomPointCollection::Remove(int32_t) เมธอด


ลบรายการออกจากคอลเลกชันโดยใช้ดัชนีของมันในคอลเลกชันจุดของซีรีส์แม่.

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| dataPointIndex | **int32_t** | ดัชนีของจุดข้อมูลในคอลเลกชันจุดของซีรีส์แม่. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IChartDataPoint](../../ichartdatapoint/)
* คลาส [PieSplitCustomPointCollection](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)