---
title: set_RawFrame()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: रॉ शैप फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें IShapeFrame।
type: docs
weight: 53
url: /hi/aspose.slides/shape/set_rawframe/
---
## Shape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) विधि


रॉ शैप फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../../ishapeframe/)।

```cpp
void Aspose::Slides::Shape::set_RawFrame(System::SharedPtr<IShapeFrame> value) override
```

## टिप्पणियाँ


कोड जो अपरिभाषित फ्रेम को [IShape::set_Frame](../../ishape/set_frame/) पर सेट करने का प्रयास करता है, सामान्य मामले में (विशेषकर जब पैरेंट [GroupShape](../../groupshape/) कई बार अन्य GroupShape-s में नेस्टेड हो) समझ में नहीं आता। उदाहरण के लिए:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
 या
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
 ऐसा कोड अस्पष्ट स्थितियों का कारण बन सकता है। इसलिए [IShape::set_Frame](../../ishape/set_frame/) के लिए अपरिभाषित मानों के उपयोग पर प्रतिबंध जोड़े गए हैं। x, y, width, height, flipH, flipV और rotationAngle के मान परिभाषित होने चाहिए (std::numeric_limits<float>::quiet_NaN() या [NullableBool::NotDefined](../../nullablebool/) नहीं)। ऊपर दिया गया उदाहरण कोड अब ArgumentException अपवाद फेंकता है। यह निम्न उपयोग मामलों पर लागू होता है:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // अपरिभाषित नहीं हो सकता

SharedPtr<IShapeCollection> shapes = ...;
// x, y, width, height पैरामीटर std::numeric_limits<float>::quiet_NaN() नहीं हो सकते:
{
    shapes->AddAudioFrameCD(...);
    shapes->AddAudioFrameEmbedded(...);
    shapes->AddAudioFrameLinked(...);
    shapes->AddAutoShape(...);
    shapes->AddChart(...);
    shapes->AddConnector(...);
    shapes->AddOleObjectFrame(...);
    shapes->AddPictureFrame(...);
    shapes->AddSmartArt(...);
    shapes->AddTable(...);
    shapes->AddVideoFrame(...);
    shapes->InsertAudioFrameEmbedded(...);
    shapes->InsertAudioFrameLinked(...);
    shapes->InsertAutoShape(...);
    shapes->InsertChart(...);
    shapes->InsertConnector(...);
    shapes->InsertOleObjectFrame(...);
    shapes->InsertPictureFrame(...);
    shapes->InsertTable(...);
    shapes->InsertVideoFrame(...);
}
```


लेकिन [IShape::set_RawFrame](../../ishape/set_rawframe/) विधि के लिए फ्रेम अपरिभाषित हो सकता है। यह तब समझ में आता है जब शैप प्लेसहोल्डर से जुड़ा हो। तब अपरिभाषित शैप फ्रेम मान पैरेंट प्लेसहोल्डर शैप से अधिलेखित हो जाते हैं। यदि उस शैप के लिए कोई पैरेंट प्लेसहोल्डर शैप नहीं है, तो वह शैप अपने [IShape::get_RawFrame](../../ishape/get_rawframe/) के आधार पर प्रभावी फ्रेम का अनुमान लगाते समय डिफ़ॉल्ट मानों का उपयोग करता है। डिफ़ॉल्ट मान x, y, width, height, flipH, flipV और rotationAngle के लिए 0 और [NullableBool::False](../../nullablebool/) हैं। उदाहरण के लिए:
```cpp
SharedPtr<IShape> shape = ...; // shape placeholder से जुड़ा है
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // अब shape x, y, height, flipH, flipV मान placeholder से विरासत में लेता है और width=100 तथा rotationAngle=0 को ओवरराइड करता है।
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IShapeFrame](../../ishapeframe/)
* क्लास [Shape](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)