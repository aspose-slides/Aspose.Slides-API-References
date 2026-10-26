---
title: get_RawFrame()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: रॉ आकार फ्रेम की गुणधर्म लौटाता है। पढ़ें IShapeFrame.
type: docs
weight: 40
url: /hi/aspose.slides/shape/get_rawframe/
---
## Shape::get_RawFrame() मेथड

रॉ आकार फ्रेम की गुणधर्म वापस करता है। पढ़ें [IShapeFrame](../../ishapeframe/).

```cpp
System::SharedPtr<IShapeFrame> Aspose::Slides::Shape::get_RawFrame() override
```

## टिप्पणी

कोड जो अनिर्धारित फ्रेम को [IShape::set_Frame](../../ishape/set_frame/) सौंपने का प्रयास करता है, सामान्य मामले में समझ में नहीं आता (विशेष रूप से जब पैरेंट [GroupShape](../../groupshape/) कई बार अन्य GroupShape-ओं में नेस्टेड हो)। उदाहरण के लिए: 
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
ऐसा कोड अस्पष्ट स्थितियों को जन्म दे सकता है। इसलिए [IShape::set_Frame](../../ishape/set_frame/) के लिए अनिर्धारित मानों के उपयोग पर प्रतिबंध लगाए गए हैं। x, y, width, height, flipH, flipV और rotationAngle के मान परिभाषित होने चाहिए (std::numeric_limits<float>::quiet_NaN() या [NullableBool::NotDefined](../../nullablebool/) नहीं)। ऊपर दिया गया उदाहरण कोड अब ArgumentException अपवाद फेंकता है। यह इन उपयोग मामलों पर लागू होता है: 
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

हालाँकि [IShape::set_RawFrame](../../ishape/set_rawframe/) मेथड के लिए फ्रेम अनिर्धारित हो सकता है। यह तब समझ में आता है जब आकार प्लेसहोल्डर से जुड़ा हो। तब अनिर्धारित आकार फ्रेम मान पैरेंट प्लेसहोल्डर आकार से अधिलेखित होते हैं। यदि उस आकार के लिए कोई पैरेंट प्लेसहोल्डर आकार नहीं है, तो वह आकार अपने [IShape::get_RawFrame](../../ishape/get_rawframe/) के आधार पर प्रभावी फ्रेम का मूल्यांकन करते समय डिफॉल्ट मानों का उपयोग करता है। डिफॉल्ट मान x, y, width, height, flipH, flipV और rotationAngle के लिए 0 और [NullableBool::False](../../nullablebool/) हैं। उदाहरण के लिए: 
```cpp
SharedPtr<IShape> shape = ...; // आकार प्लेसहोल्डर से जुड़ा है
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // अब आकार प्लेसहोल्डर से x, y, height, flipH, flipV मानों को विरासत में लेता है और width=100 तथा rotationAngle=0 को ओवरराइड करता है।
```

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IShapeFrame](../../ishapeframe/)
* क्लास [Shape](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)