---
title: Add()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: เพิ่ม Tab ไปยังคอลเลกชัน.
type: docs
weight: 14
url: /th/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) เมธอด

เพิ่ม [Tab](../../tab/) ไปยังคอลเลกชัน.

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) ตำแหน่ง. |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) การจัดแนว. |

### ค่าที่คืน

แท็บที่เพิ่ม.

## ITabCollection::Add(System::SharedPtr\<ITab\>) เมธอด

เพิ่ม [Tab](../../tab/) ไปยังคอลเลกชัน.

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | วัตถุ [Tab](../../tab/) ที่จะเพิ่มที่ท้ายของคอลเลกชัน. |

### ค่าที่คืน

ดัชนีที่แท็บถูกเพิ่ม.

## ดูเพิ่มเติม

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ITab](../../itab/)
* คลาส [ITabCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)