---
title: GetEffective()
second_title: Aspose.Slides for C++ API संदर्भ
description: विरासत लागू होते हुए प्रभावी 3-D फ़ॉर्मेटिंग डेटा प्राप्त करता है।
type: docs
weight: 183
url: /hi/aspose.slides/threedformat/geteffective/
---
## ThreeDFormat::GetEffective() मेथड


विरासत लागू होने पर प्रभावी 3-D फ़ॉर्मेटिंग डेटा प्राप्त करता है।

```cpp
System::SharedPtr<IThreeDFormatEffectiveData> Aspose::Slides::ThreeDFormat::GetEffective() override
```


### रिटर्न वैल्यू

एक [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/).
## टिप्पणी



यह उदाहरण दिखाता है कि कैमरा, लाइट रिग और आकार के शीर्ष बिवेल के प्रभावी गुण कैसे प्राप्त करें। 
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

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/)
* Class [ThreeDFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)