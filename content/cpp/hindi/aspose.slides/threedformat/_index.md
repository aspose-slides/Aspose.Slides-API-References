---
title: ThreeDFormat
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: 3-D गुणों का प्रतिनिधित्व करता है।
type: docs
weight: 5513
url: /hi/aspose.slides/threedformat/
---
## ThreeDFormat क्लास

3-D गुणों का प्रतिनिधित्व करता है।

```cpp
class ThreeDFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IThreeDFormat
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | निर्दिष्ट वस्तु के साथ तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस्‍ट प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevel](../ishapebevel/)\> [get_BevelBottom](./get_bevelbottom/)() override | निचले 3D बीवेल का प्रकार लौटाता है। केवल-पठन [IShapeBevel](../ishapebevel/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevel](../ishapebevel/)\> [get_BevelTop](./get_beveltop/)() override | ऊपरी 3D बीवेल का प्रकार लौटाता है। केवल-पठन [IShapeBevel](../ishapebevel/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICamera](../icamera/)\> [get_Camera](./get_camera/)() override | कैमरा की सेटिंग्स लौटाता है। केवल-पठन [ICamera](../icamera/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_ContourColor](./get_contourcolor/)() override | कॉन्टूर का रंग लौटाता है। केवल-पठन [IColorFormat](../icolorformat/)। |
| **double** [get_ContourWidth](./get_contourwidth/)() override | 3D कॉन्टूर की चौड़ाई लौटाता है। **double** पढ़ें। |
| **double** [get_Depth](./get_depth/)() override | 3D आकार की गहराई लौटाता है। **double** पढ़ें। |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_ExtrusionColor](./get_extrusioncolor/)() override | एक एक्सट्रूज़न का रंग लौटाता है। केवल-पठन [IColorFormat](../icolorformat/)। |
| **double** [get_ExtrusionHeight](./get_extrusionheight/)() override | एक एक्सट्रूज़न प्रभाव की ऊँचाई लौटाता है। **double** पढ़ें। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILightRig](../ilightrig/)\> [get_LightRig](./get_lightrig/)() override | लाइट का प्रकार लौटाता है। केवल-पठन [ILightRig](../ilightrig/)। |
| [MaterialPresetType](../materialpresettype/) [get_Material](./get_material/)() override | सामग्री का प्रकार लौटाता है। [MaterialPresetType](../materialpresettype/) पढ़ें। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पठन [IDOMObject](../idomobject/)। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | पेरेंट [IPresentationComponent](../ipresentationcomponent/) लौटाता है। केवल-पठन [IPresentationComponent](../ipresentationcomponent/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंसम् काउंटर डेटा संरचना प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormatEffectiveData](../ithreedformateffectivedata/)\> [GetEffective](./geteffective/)() override | विरासत लागू करके प्रभावी 3-D फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | हैश कोड लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का analog। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचें कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का analog। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का analog। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा मान प्रकार के ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के मामले के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_ContourWidth](./set_contourwidth/)(**double**) override | 3D कॉन्टूर की चौड़ाई सेट करता है। **double** लिखें। |
| void [set_Depth](./set_depth/)(**double**) override | 3D आकार की गहराई सेट करता है। **double** लिखें। |
| void [set_ExtrusionHeight](./set_extrusionheight/)(**double**) override | एक एक्सट्रूज़न प्रभाव की ऊँचाई सेट करता है। **double** लिखें। |
| void [set_Material](./set_material/)([MaterialPresetType](../materialpresettype/)) override | सामग्री का प्रकार सेट करता है। [MaterialPresetType](../materialpresettype/) लिखें। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता और लौटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का analog। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टिप्पणियाँ

निम्न उदाहरण PowerPoint [Presentation](../presentation/) में 3D आकार जोड़ने का तरीका दिखाता है। 
```cpp
// Presentation क्लास का एक इंस्टेंस बनाएं।
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Add a shape using AddAutoShape method
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 150.0f, 200.0f, 200.0f);

// Define TextFrame and its properties
shape->get_TextFrame()->set_Text(u"3D");
shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_DefaultPortionFormat()->set_FontHeight(64.0f);

// Define ThreeDFormat Properties
auto threeDFormat = shape->get_ThreeDFormat();
threeDFormat->get_Camera()->set_CameraType(CameraPresetType::OrthographicFront);
threeDFormat->get_Camera()->SetRotation(20.0f, 30.0f, 40.0f);
threeDFormat->get_LightRig()->set_LightType(LightRigPresetType::Flat);
threeDFormat->get_LightRig()->set_Direction(LightingDirection::Top);
threeDFormat->set_Material(MaterialPresetType::Flat);
threeDFormat->set_ExtrusionHeight(100);
threeDFormat->get_ExtrusionColor()->set_Color(System::Drawing::Color::get_Blue());
slide->GetThumbnail(2.0f, 2.0f)->Save(u"sample_3d.png");

// Save the Presentation file
pres->Save(u"sandbox_3d.pptx", SaveFormat::Pptx);
```
निम्न उदाहरण PowerPoint [Presentation](../presentation/) में 3D आकार पर ग्रेडिएंट प्रभाव लागू करने का तरीका दिखाता है। 
```cpp
// Presentation क्लास का एक इंस्टेंस बनाएं।
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// AddAutoShape मेथड का उपयोग करके एक शेप जोड़ें
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 150.0f, 250.0f, 250.0f);

// TextFrame और इसके गुण निर्धारित करें
shape->get_TextFrame()->set_Text(u"3D Gradient");
shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_DefaultPortionFormat()->set_FontHeight(64.0f);

// FillFormat.FillType को FillType.Gradient के रूप में सेट करें और ग्रेडिएंट गुण निर्धारित करें
shape->get_FillFormat()->set_FillType(FillType::Gradient);
shape->get_FillFormat()->get_GradientFormat()->get_GradientStops()->Add(0.0f, System::Drawing::Color::get_Blue());
shape->get_FillFormat()->get_GradientFormat()->get_GradientStops()->Add(100.0f, System::Drawing::Color::get_Orange());

// ThreeDFormat गुण निर्धारित करें
auto threeDFormat = shape->get_ThreeDFormat();
threeDFormat->get_Camera()->set_CameraType(CameraPresetType::OrthographicFront);
threeDFormat->get_Camera()->SetRotation(20.0f, 30.0f, 40.0f);
threeDFormat->get_LightRig()->set_LightType(LightRigPresetType::Flat);
threeDFormat->get_LightRig()->set_Direction(LightingDirection::Top);
threeDFormat->set_Material(MaterialPresetType::Flat);
threeDFormat->set_ExtrusionHeight(100);
threeDFormat->get_ExtrusionColor()->set_Color(System::Drawing::Color::get_Blue());
slide->GetThumbnail(2.0f, 2.0f)->Save(u"sample_3d.png");

// Presentation फ़ाइल सहेजें
pres->Save(u"sandbox_3d.pptx", SaveFormat::Pptx);
```
निम्न उदाहरण टेक्स्ट पर 3D प्रभाव लागू करने का तरीका दिखाता है। 3D टेक्स्ट बनाने के लिए WordArt ट्रांसफ़ॉर्म प्रभाव का उपयोग संभव है। 
```cpp
// Presentation क्लास का एक इंस्टेंस बनाएं।
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// AddAutoShape मेथड का उपयोग करके एक शेप जोड़ें
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 150.0f, 250.0f, 250.0f);

// TextFrame और उसकी प्रॉपर्टीज़ निर्धारित करें
shape->get_TextFrame()->set_Text(u"3D Text");

// FillFormat.FillType को FillType.NoFill के रूप में सेट करें
shape->get_FillFormat()->set_FillType(FillType::NoFill);
shape->get_LineFormat()->get_FillFormat()->set_FillType(FillType::NoFill);

// TextFrame के Portion को कॉन्फ़िगर करें और PortionFormat की प्रॉपर्टीज़ सेट करें
System::SharedPtr<Portion> portion = System::ExplicitCast<Portion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0));
portion->get_PortionFormat()->get_FillFormat()->set_FillType(FillType::Pattern);
portion->get_PortionFormat()->get_FillFormat()->get_PatternFormat()->get_ForeColor()->set_Color(System::Drawing::Color::get_DarkOrange());
portion->get_PortionFormat()->get_FillFormat()->get_PatternFormat()->get_BackColor()->set_Color(System::Drawing::Color::get_White());
portion->get_PortionFormat()->get_FillFormat()->get_PatternFormat()->set_PatternStyle(PatternStyle::LargeGrid);
shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_DefaultPortionFormat()->set_FontHeight(128.0f);
System::SharedPtr<ITextFrame> textFrame = shape->get_TextFrame();

// "Arch Up" WordArt ट्रांसफ़ॉर्म इफ़ेक्ट सेट अप करें
textFrame->get_TextFrameFormat()->set_Transform(TextShapeType::ArchUp);

// ITextFrame की ThreeDFormat प्रॉपर्टीज़ निर्धारित करें
auto threeDFormat = textFrame->get_TextFrameFormat()->get_ThreeDFormat();
threeDFormat->set_ExtrusionHeight(3.5f);
threeDFormat->set_Depth(3);
threeDFormat->set_Material(MaterialPresetType::Plastic);
threeDFormat->get_LightRig()->set_Direction(LightingDirection::Top);
threeDFormat->get_LightRig()->set_LightType(LightRigPresetType::Balanced);
threeDFormat->get_LightRig()->SetRotation(0.0f, 0.0f, 40.0f);
threeDFormat->get_Camera()->set_CameraType(CameraPresetType::PerspectiveContrastingRightFacing);
slide->GetThumbnail(2.0f, 2.0f)->Save(u"text3d.png");

// Presentation फ़ाइल सहेजें
pres->Save(u"text3d.pptx", SaveFormat::Pptx);
```

## देखें

* क्लास [PVIObject](../pviobject/)
* क्लास [IThreeDFormat](../ithreedformat/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)