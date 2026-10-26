---
title: Insert()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แทรกองค์ประกอบคณิตศาสตร์ลงในคอลเลกชันที่ตำแหน่งที่ระบุ
type: docs
weight: 53
url: /th/aspose.slides.mathtext/imathelementcollection/insert/
---
## IMathElementCollection::Insert(int32_t, System::SharedPtr\<IMathElement\>) เมธอด

แทรกองค์ประกอบคณิตศาสตร์ลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::Insert(int32_t index, System::SharedPtr<IMathElement> item)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์ซึ่ง [IMathElement](../../imathelement/) ควรถูกแทรก |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | [IMathElement](../../imathelement/) ที่จะทำการแทรก |
## หมายเหตุ


ตัวอย่าง: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [IMathElementCollection](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)