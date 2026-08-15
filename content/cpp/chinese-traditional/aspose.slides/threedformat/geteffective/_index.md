---
title: GetEffective()
second_title: Aspose.Slides for C++ API 參考
description: 取得套用繼承後的實際 3-D 格式化資料。
type: docs
weight: 183
url: /zh-hant/aspose.slides/threedformat/geteffective/
---
## ThreeDFormat::GetEffective() 方法


取得套用繼承後的實際 3-D 格式化資料。

```cpp
System::SharedPtr<IThreeDFormatEffectiveData> Aspose::Slides::ThreeDFormat::GetEffective() override
```


### 返回值

A [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/).
## 備註



此範例示範如何取得相機、光源裝置與形狀上斜角的實際屬性。 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto threeDEffectiveData = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_ThreeDFormat()->GetEffective();

Console::WriteLine(u"= Effective camera properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_Camera()->get_CameraType()));
Console::WriteLine(String(u"Field of view: ") + threeDEffectiveData->get_Camera()->get_FieldOfViewAngle());
Console::WriteLine(String(u"Zoom: ") + threeDEffectiveData->get_Camera()->get_Zoom());

Console::WriteLine(u"= Effective light rig properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_LightRig()->get_LightType()));
Console::WriteLine(String(u"Direction: ") + ObjectExt::ToString(threeDEffectiveData->get_LightRig()->get_Direction()));

Console::WriteLine(u"= Effective shape's top face relief properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_BevelTop()->get_BevelType()));
Console::WriteLine(String(u"Width: ") + threeDEffectiveData->get_BevelTop()->get_Width());
Console::WriteLine(String(u"Height: ") + threeDEffectiveData->get_BevelTop()->get_Height());
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/)
* 類別 [ThreeDFormat](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)