---
title: MathBlock()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: สร้างอินสแตนซ์ใหม่ของคลาส MathBlock.
type: docs
weight: 66
url: /th/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() คอนสตรัคเตอร์


สร้างอินสแตนซ์ใหม่ของคลาส [MathBlock](../).

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) คอนสตรัคเตอร์


สร้างบล็อกคณิตศาสตร์ใหม่และใส่องค์ประกอบที่ระบุลงในบล็อก

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | องค์ประกอบคณิตศาสตร์ที่ใส่ลงในบล็อก |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) คอนสตรัคเตอร์


สร้างบล็อกคณิตศาสตร์ใหม่และใส่องค์ประกอบที่ระบุลงในบล็อก

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | องค์ประกอบคณิตศาสตร์ที่ใส่ลงในบล็อก |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [MathBlock](../)
* คลาส [IMathElement](../../imathelement/)
* คลาส [IEnumerable](../../../system.collections.generic/ienumerable/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)