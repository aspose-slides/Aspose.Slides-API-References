---
title: CopyTo()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คัดลอกไปยังอาเรย์ที่ระบุ.
type: docs
weight: 118
url: /th/aspose.slides.mathtext/imathelementcollection/copyto/
---
## IMathElementCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IMathElement\>\>, int32_t) เมธอด

คัดลอกไปยังอาเรย์ที่ระบุ.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IMathElement>> array, int32_t arrayIndex)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\> | อาเรย์ที่คัดลอกไป |
| arrayIndex | **int32_t** | ดัชนีเริ่มต้นการคัดลอก |
## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<IMathElementCollection> collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
auto destinationArray = System::MakeArray<System::SharedPtr<IMathElement>>(collection->get_Count());
collection->CopyTo(destinationArray, 0);
```

## ดูเพิ่มเติม

* ประเภทนิยาม [ArrayPtr](../../../system/arrayptr/)
* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [IMathElementCollection](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)