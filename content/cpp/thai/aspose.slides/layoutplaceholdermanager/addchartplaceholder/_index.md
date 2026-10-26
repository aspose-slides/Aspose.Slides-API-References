---
title: AddChartPlaceholder()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: เพิ่มรูปทรงตัวจับตำแหน่งใหม่ลงในสไลด์เค้าโครงเพื่อใส่แผนภูมิ.
type: docs
weight: 66
url: /th/aspose.slides/layoutplaceholdermanager/addchartplaceholder/
---
## LayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) method

เพิ่มรูปทรงตัวจับตำแหน่งใหม่ลงในสไลด์เค้าโครงเพื่อใส่ **Chart**.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | พิกัด X ของรูปทรงตัวจับตำแหน่งใหม่ |
| y | **float** | พิกัด Y ของรูปทรงตัวจับตำแหน่งใหม่ |
| width | **float** | ความกว้างของรูปทรงตัวจับตำแหน่งใหม่ |
| height | **float** | ความสูงของรูปทรงตัวจับตำแหน่งใหม่ |

### Return Value

สร้าง [IAutoShape](../../iautoshape/) พร้อมกับตัวจับตำแหน่ง **Chart**.

## Remarks

ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มรูปทรงตัวจับตำแหน่ง **Chart** ลงในสไลด์เค้าโครง. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)