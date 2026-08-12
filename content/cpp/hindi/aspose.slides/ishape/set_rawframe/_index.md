---
title: set_RawFrame()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: रॉ शैप फ्रेम की गुणधर्म सेट करता है। IShapeFrame लिखें।
type: docs
weight: 53
url: /hi/aspose.slides/ishape/set_rawframe/
---
## IShape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) विधि

रॉ शैप फ्रेम की गुणधर्म सेट करता है। लिखें [IShapeFrame](../../ishapeframe/).

```cpp
virtual void Aspose::Slides::IShape::set_RawFrame(System::SharedPtr<IShapeFrame> value)=0
```

## टिप्पणी

कोड जो अपरिभाषित फ्रेम को [IShape::set_Frame](../set_frame/) को असाइन करने का प्रयास करता है, सामान्य मामले में समझ में नहीं आता (विशेषकर उस स्थिति में जब पेरेंट [GroupShape](../../groupshape/) कई बार अन्य GroupShape-में नेस्टेड हो)। उदाहरण के लिए:
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
ऐसा कोड अस्पष्ट स्थितियों का कारण बन सकता है। इसलिए [IShape::set_Frame](../set_frame/) के लिए अपरिभाषित मानों के उपयोग पर प्रतिबंध जोड़े गए हैं। x, y, width, height, flipH, flipV और rotationAngle के मान परिभाषित होने चाहिए (std::numeric_limits<float>::quiet_NaN() या [NullableBool::NotDefined](../../nullablebool/) नहीं)। ऊपर दिया गया उदाहरण कोड अब ArgumentException अपवाद फेंकता है। यह निम्न उपयोग मामलों पर लागू होता है:
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
लेकिन [IShape::set_RawFrame](./) विधि के लिए फ्रेम अपरिभाषित हो सकता है। यह तब समझ में आता है जब आकार (shape) प्लेसहोल्डर से जुड़ा हो। तब अपरिभाषित आकार फ्रेम मान पैरेंट प्लेसहोल्डर आकार से ओवरराइड हो जाते हैं। यदि उस आकार के लिए कोई पैरेंट प्लेसहोल्डर आकार नहीं है तो वह आकार अपने [IShape::get_RawFrame](../get_rawframe/) के आधार पर प्रभावी फ्रेम का मूल्यांकन करते समय डिफ़ॉल्ट मान उपयोग करता है। डिफ़ॉल्ट मान x, y, width, height, flipH, flipV और rotationAngle के लिए 0 और [NullableBool::False](../../nullablebool/) हैं। उदाहरण के लिए:
```cpp
SharedPtr<IShape> shape = ...; // shape प्लेसहोल्डर से जुड़ा है
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // अब shape प्लेसहोल्डर से x, y, height, flipH, flipV मान विरासत में लेता है और width=100 और rotationAngle=0 को ओवरराइड करता है।
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IShapeFrame](../../ishapeframe/)
* क्लास [IShape](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)