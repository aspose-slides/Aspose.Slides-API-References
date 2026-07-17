---
title: get_ThreeDFormat()
second_title: Aspose.Slides C++ API 参考
description: 返回表示文本 3d 效果属性的 ThreeDFormat 对象。只读 IThreeDFormat.
type: docs
weight: 300
url: /zh/aspose.slides/itextframeformat/get_threedformat/
---
## ITextFrameFormat::get_ThreeDFormat() 方法


返回 [ThreeDFormat](../../threedformat/) 对象，表示文本的 3d 效果属性。只读 [IThreeDFormat](../../ithreedformat/)。

```cpp
virtual System::SharedPtr<IThreeDFormat> Aspose::Slides::ITextFrameFormat::get_ThreeDFormat()=0
```

## 备注



```cpp
using namespace Aspose::Slides;

auto pres = System::MakeObject<Presentation>();
auto autoShape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 20.0f, 400.0f, 300.0f);
auto textFrame = autoShape->get_TextFrame();

textFrame->set_Text(u"Aspose.Slide Test Text");

// Set text transformation
textFrame->get_TextFrameFormat()->set_Transform(TextShapeType::ArchUpPour);

// Set Extrusion
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->get_ExtrusionColor()->set_Color(System::Drawing::Color::get_Orange());
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->set_ExtrusionHeight(6);

// Set Contour
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->get_ContourColor()->set_Color(System::Drawing::Color::get_DarkRed());
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->set_ContourWidth(1.5);

// Set Depth
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->set_Depth(3);

// Set Material
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->set_Material(MaterialPresetType::Plastic);

// Set Lighting
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->get_LightRig()->set_Direction(LightingDirection::Top);
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->get_LightRig()->set_LightType(LightRigPresetType::Balanced);
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->get_LightRig()->SetRotation(0.0f, 0.0f, 40.0f);

// Set camera type
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->get_Camera()->set_CameraType(CameraPresetType::PerspectiveContrastingRightFacing);
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IThreeDFormat](../../ithreedformat/)
* 类 [ITextFrameFormat](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)