---
title: Image
second_title: Aspose.Slides for C++ API संदर्भ
description: "System::Drawing::Bitmap और System::Drawing::Metafile क्लासों के लिए बुनियादी कार्यक्षमता प्रदान करने वाली आधार क्लास। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या एसेर्शन त्रुटियाँ उत्पन्न होंगी। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों में तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 144
url: /hi/system.drawing/image/
---
## Image क्लास

बेस क्लास जो [System::Drawing::Bitmap](../bitmap/) और System::Drawing::Metafile क्लासों के लिए बुनियादी कार्यक्षमता प्रदान करता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या एसेर्शन त्रुटियाँ उत्पन्न होंगी। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शनों में तर्क के रूप में पास करें।

```cpp
class Image : public virtual System::IDisposable
```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Image](./)\> [Clone](./clone/)() | वर्तमान वस्तु की एक प्रति बनाता है। |
| void [Dispose](./dispose/)() override | वर्तमान वस्तु द्वारा प्राप्त सभी संसाधनों को रिलीज़ करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उद्देश्यों के लिए। |
| static [SharedPtr](../../system/sharedptr/)\<[Image](./)\> [FromFile](./fromfile/)(const [String](../../system/string/)\&, **bool**) | निर्दिष्ट फ़ाइल से एक [Image](./) वस्तु बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](../bitmap/)\> [FromHbitmap](./fromhbitmap/)(IntPtr) | निर्दिष्ट GDI बिटमैप से एक [Bitmap](../bitmap/) वस्तु बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[Image](./)\> [FromStream](./fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | निर्दिष्ट स्ट्रीम से एक [Image](./) वस्तु बनाता है। |
| virtual **int32_t** [get_Flags](./get_flags/)() const | इमेज के गुणों को दर्शाने वाले ImageFlags enum मानों का बिट-वाइज संयोजन लौटाता है। |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](./get_framedimensionslist/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इमेज के फ्रेम के आयामों को दर्शाने वाले GUIDs की एक एरे लौटाता है। |
| virtual int [get_Height](./get_height/)() const | इमेज की ऊँचाई पिक्सेल में लौटाता है। |
| **float** [get_HorizontalResolution](./get_horizontalresolution/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इमेज का क्षैतिज रिज़ॉल्यूशन पिक्सेल प्रति इंच में लौटाता है। |
| virtual [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इमेज द्वारा उपयोग किया गया रंग पैलेट लौटाता है। |
| virtual [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इमेज का पिक्सेल फॉर्मेट लौटाता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](./get_propertyidlist/)() const | इस इमेज में संग्रहित प्रॉपर्टी आइटम्स के IDs प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](./get_propertyitems/)() const | इस इमेज में संग्रहित सभी प्रॉपर्टी आइटम्स (मेटाडाटा के टुकड़े) प्राप्त करता है। |
| virtual [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इमेज के फ़ाइल फ़ॉर्मेट को लौटाता है। |
| [Size](../size/) [get_Size](./get_size/)() const | इमेज की चौड़ाई और ऊँचाई पिक्सेल में दर्शाने वाला [Size](../size/) वस्तु लौटाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](./get_tag/)() const | इमेज के बारे में अतिरिक्त डेटा प्रदान करने वाला वस्तु प्राप्त करता है। |
| **float** [get_VerticalResolution](./get_verticalresolution/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इमेज का लंबवत रिज़ॉल्यूशन पिक्सेल प्रति इंच में लौटाता है। |
| virtual int [get_Width](./get_width/)() const | इमेज की चौड़ाई पिक्सेल में लौटाता है। |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)([GraphicsUnit](../graphicsunit/)\&) | निर्दिष्ट माप इकाइयों में इमेज की सीमा लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से संबद्ध रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| int [GetFrameCount](./getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | निर्दिष्ट फ्रेम आयाम के फ्रेमों की संख्या लौटाता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम वस्तुओं का हैशिंग सक्षम करता है। |
| static int [GetPixelFormatSize](./getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | निर्दिष्ट पिक्सेल फॉर्मेट में रंग गहराई को दर्शाने के लिए उपयोग किए गए बिटों की संख्या लौटाता है। |
| virtual const SkBitmap * [GetSkBitmap](./getskbitmap/)() const | अंतर्निहित SkBitmap वस्तु लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Image](./)\> [GetThumbnailImage](./getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](./getthumbnailimageabort/), IntPtr) | इस [System::Drawing::Image](./) वस्तु के लिए थंबनेल प्राप्त करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि वस्तु targetType द्वारा वर्णित प्रकार की एक इंस्टेंस का प्रतिनिधित्व करती है। C# 'is' ऑपरेटर का समकक्ष। |
| static **bool** [IsAlphaPixelFormat](./isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | निर्दिष्ट पिक्सेल फॉर्मेट में अल्फा जानकारी है या नहीं निर्धारित करता है। |
| virtual **bool** [IsMultiImage](./ismultiimage/)() const | मूल फ़ॉर्मेट मल्टी-इमेज है या नहीं लौटाता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री वस्तु का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | वस्तु बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कॉन्स्ट्रकटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया वस्तु इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया वस्तु इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस के साथ वैल्यू टाइप वस्तु की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) | इमेज को 90 डिग्री के गुणक तक घुमाता है और फ्लिप करता है। |
| void [Save](./save/)(const [String](../../system/string/)\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इमेज को PNG फ़ॉर्मेट में निर्दिष्ट फ़ाइल में सेव करता है। |
| void [Save](./save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इमेज को निर्दिष्ट फ़ॉर्मेट में निर्दिष्ट फ़ाइल में सेव करता है। |
| void [Save](./save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इमेज को निर्दिष्ट फ़ॉर्मेट में निर्दिष्ट स्ट्रीम में सेव करता है। |
| void [Save](./save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इमेज को निर्दिष्ट एन्कोडर और एन्कोडर पैरामीटरों का उपयोग करके निर्दिष्ट फ़ाइल में सेव करता है। |
| void [Save](./save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इमेज को निर्दिष्ट एन्कोडर और एन्कोडर पैरामीटरों का उपयोग करके निर्दिष्ट स्ट्रीम में सेव करता है। |
| void [SaveAdd](./saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | [Save()](./save/) मेथड के पिछले कॉल में निर्दिष्ट फ़ाइल या स्ट्रीम में एक फ्रेम जोड़ता है। |
| void [SaveAdd](./saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](./)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | [Save()](./save/) मेथड के पिछले कॉल में निर्दिष्ट फ़ाइल या स्ट्रीम में एक फ्रेम जोड़ता है। |
| int [SelectActiveFrame](./selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | निर्दिष्ट फ्रेम का चयन करता है। |
| virtual void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इमेज द्वारा उपयोग किए गए रंग पैलेट को सेट करता है। |
| virtual void [set_Tag](./set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | इमेज के बारे में अतिरिक्त डेटा प्रदान करने वाले वस्तु को सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्गुमेंट को एक weak पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम वस्तुओं को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री वस्तु का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | वस्तु को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टाइपडिफ़्स

| टाइपडिफ़ | विवरण |
| --- | --- |
| [GetThumbnailImageAbort](./getthumbnailimageabort/) | GetThumbnailImage निष्पादन को रद्द करने के लिए एक कॉलबैक। |

## देखें

* क्लास [IDisposable](../../system/idisposable/)
* नेमस्पेस [System::Drawing](../)
* लाइब्रेरी [Aspose.Slides](../../)