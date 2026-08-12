---
title: MathArray()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: สร้างอาร์เรย์คณิตศาสตร์และวางองค์ประกอบที่ระบุไว้ในอาร์เรย์
type: docs
weight: 144
url: /th/aspose.slides.mathtext/matharray/matharray/
---
## MathArray::MathArray(System::SharedPtr\<IMathElement\>) คอนสตรัคเตอร์

สร้างอาร์เรย์คณิตศาสตร์และวางองค์ประกอบที่ระบุลงในอาร์เรย์

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<IMathElement> element)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | องค์ประกอบที่จะวางในอาร์เรย์ |

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
```

## MathArray::MathArray(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) คอนสตรัคเตอร์

สร้างอาร์เรย์คณิตศาสตร์และวางองค์ประกอบที่ระบุหลายรายการลงในอาร์เรย์

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> elements)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| elements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | องค์ประกอบที่จะวางในอาร์เรย์ |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathArray](../)
* คลาส [IEnumerable](../../../system.collections.generic/ienumerable/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)