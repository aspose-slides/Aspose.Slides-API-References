---
title: Bitmap
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक GDI+ बिटमैप छवि का प्रतिनिधित्व करता है। इस वर्ग की ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फ़ॉल्ट्स उत्पन्न हो सकते हैं। हमेशा इस वर्ग को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 1
url: /hi/system.drawing/bitmap/
---
## Bitmap वर्ग

एक GDI+ बिटमैप छवि का प्रतिनिधित्व करता है। इस वर्ग की ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या assertion त्रुटियाँ उत्पन्न होंगी। हमेशा इस वर्ग को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को तर्क के रूप में फ़ंक्शनों को पास करने के लिए उपयोग करें।

```cpp
class Bitmap : public System::Drawing::Image
```

## Methods

| विधि | विवरण |
| --- | --- |
| **bool** [BeginPixelProcessing](./beginpixelprocessing/)(**bool**) | पिक्सेल प्रोसेसिंग मोड को सक्षम करता है। |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | निर्दिष्ट मौजूदा छवि से नया [Bitmap](./) ऑब्जेक्ट बनाता है। |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**) | निर्दिष्ट स्ट्रीम से नया [Bitmap](./) ऑब्जेक्ट बनाता है। |
|  [Bitmap](./bitmap/)(const [String](../../system/string/)\&) | निर्दिष्ट फ़ाइल से नया [Bitmap](./) ऑब्जेक्ट बनाता है। |
|  [Bitmap](./bitmap/)(const [String](../../system/string/)\&, **bool**) | निर्दिष्ट फ़ाइल से नया [Bitmap](./) ऑब्जेक्ट बनाता है। |
|  [Bitmap](./bitmap/)(int, int, [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | निर्दिष्ट चौड़ाई, ऊंचाई, पिक्सेल फ़ॉर्मेट और पिक्सेल डेटा के साथ एक बिटमैप छवि का प्रतिनिधित्व करने वाला नया [Bitmap](./) ऑब्जेक्ट बनाता है। |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Size](../size/)\&) | निर्दिष्ट मौजूदा छवि को निर्दिष्ट आकार में स्केल करके नया [Bitmap](./) ऑब्जेक्ट बनाता है। |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | निर्दिष्ट मौजूदा छवि से चौड़ाई और ऊंचाई को निर्दिष्ट मूल्यों में स्केल करके नया [Bitmap](./) ऑब्जेक्ट बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [Clone](./clone/)() override | वर्तमान ऑब्जेक्ट की एक प्रतिलिपि बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([Rectangle](../rectangle/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए बिटमैप छवि के एक क्षेत्र की प्रतिलिपि का प्रतिनिधित्व करने वाला [Bitmap](./) ऑब्जेक्ट बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([RectangleF](../rectanglef/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए बिटमैप छवि के एक क्षेत्र की प्रतिलिपि का प्रतिनिधित्व करने वाला [Bitmap](./) ऑब्जेक्ट बनाता है। |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](./computehash/)() | SHA1 हैश मान की गणना करता है। |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [ConvertToARGBImage](./converttoargbimage/)(const [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\>\&) | पिक्सेल फ़ॉर्मेट को Format32bppArgb में बदलकर निर्दिष्ट बिटमैप छवि की प्रतिलिपि बनाता है। |
| void [Dispose](../image/dispose/)() override | वर्तमान ऑब्जेक्ट द्वारा प्राप्त सभी संसाधनों को रिलीज़ करता है। |
| **bool** [EndPixelProcessing](./endpixelprocessing/)(**bool**) | पिक्सेल प्रोसेसिंग मोड को अक्षम करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) अभिप्रायों का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromFile](../image/fromfile/)(const [String](../../system/string/)\&, **bool**) | निर्दिष्ट फ़ाइल से एक [Image](../image/) ऑब्जेक्ट बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [FromHbitmap](../image/fromhbitmap/)(IntPtr) | निर्दिष्ट GDI बिटमैप से एक [Bitmap](./) ऑब्जेक्ट बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromStream](../image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | निर्दिष्ट स्ट्रीम से एक [Image](../image/) ऑब्जेक्ट बनाता है। |
| virtual **int32_t** [get_Flags](../image/get_flags/)() const | छवि के गुणों का प्रतिनिधित्व करने वाले ImageFlags enum मानों का बिट-वार संयोजन लौटाता है। |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../image/get_framedimensionslist/)() const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व की गई छवि के फ्रेमों के आयामों का प्रतिनिधित्व करने वाले GUIDs की एक एरे लौटाता है। |
| int [get_Height](./get_height/)() const override | छवि की ऊंचाई पिक्सेल में लौटाता है। |
| **float** [get_HorizontalResolution](../image/get_horizontalresolution/)() const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व की गई छवि का क्षैतिज रिज़ॉल्यूशन पिक्सेल प्रति इंच में लौटाता है। |
| [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const override | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व की गई छवि द्वारा उपयोग किए गए रंग पैलेट को लौटाता है। |
| [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व की गई छवि का पिक्सेल फ़ॉर्मेट लौटाता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../image/get_propertyidlist/)() const | इस छवि में संग्रहीत प्रॉपर्टी आइटम्स के ID प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](../image/get_propertyitems/)() const | इस छवि में संग्रहीत सभी प्रॉपर्टी आइटम्स (मेटाडेटा के टुकड़े) प्राप्त करता है। |
| [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व की गई छवि का फ़ाइल फ़ॉर्मेट लौटाता है। |
| [Size](../size/) [get_Size](../image/get_size/)() const | छवि की चौड़ाई और ऊंचाई को पिक्सेल में दर्शाने वाले एक [Size](../size/) ऑब्जेक्ट को लौटाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../image/get_tag/)() const | छवि के बारे में अतिरिक्त डेटा प्रदान करने वाला ऑब्जेक्ट प्राप्त करता है। |
| **float** [get_VerticalResolution](../image/get_verticalresolution/)() const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व की गई छवि का ऊर्ध्वाधर रिज़ॉल्यूशन पिक्सेल प्रति इंच में लौटाता है। |
| int [get_Width](./get_width/)() const override | छवि की चौड़ाई पिक्सेल में लौटाता है। |
| [RectangleF](../rectanglef/) [GetBounds](../image/getbounds/)([GraphicsUnit](../graphicsunit/)\&) | निर्दिष्ट माप इकाइयों में छवि की सीमाएं लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| int [GetFrameCount](../image/getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | निर्दिष्ट फ्रेम डाइमेंशन की फ्रेमों की संख्या लौटाता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| IntPtr [GetHbitmap](./gethbitmap/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए बिटमैप से एक GDI बिटमैप ऑब्जेक्ट बनाता है। |
| [Color](../color/) [GetPixel](./getpixel/)(int, int) | निर्दिष्ट पिक्सेल का रंग लौटाता है। |
| static int [GetPixelFormatSize](../image/getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | निर्दिष्ट पिक्सेल फ़ॉर्मेट में रंग गहराई को दर्शाने के लिए उपयोग किए गए बिट्स की संख्या लौटाता है। |
| const SkBitmap * [GetSkBitmap](./getskbitmap/)() const override | अधोस्त SkBitmap ऑब्जेक्ट का एक कच्चा पॉइंटर लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [GetThumbnailImage](../image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../image/getthumbnailimageabort/), IntPtr) | इस [System::Drawing::Image](../image/) ऑब्जेक्ट के लिए एक थंबनेल प्राप्त करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| static **bool** [IsAlphaPixelFormat](../image/isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | निर्दिष्ट पिक्सेल फ़ॉर्मेट में अल्फा जानकारी है या नहीं निर्धारित करता है। |
| **bool** [IsMultiImage](./ismultiimage/)() const override | मूल फ़ॉर्मेट एक मल्टी-इमेज है या नहीं लौटाता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | एक [Bitmap](./) को सिस्टम स्मृति में लॉक करता है। |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/), const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | एक [Bitmap](./) को सिस्टम स्मृति में लॉक करता है। |
| void [MakeTransparent](./maketransparent/)([Color](../color/)) | निर्दिष्ट रंग वाले सभी पिक्सेल्स का रंग पारदर्शी में बदलता है। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तविक में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तविक में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| void [PremultipleColors](./premultiplecolors/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए छवि के पिक्सेल रंगों को प्रीमल्टिप्लाई करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ करती है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) override | छवि को 90 डिग्री के गुणज पर घुमाता है और पलटता है। |
| void [Save](../image/save/)(const [String](../../system/string/)\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व की गई छवि को निर्दिष्ट फ़ाइल में PNG फ़ॉर्मेट में सहेजता है। |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व की गई छवि को निर्दिष्ट फ़ाइल में निर्दिष्ट फ़ॉर्मेट में सहेजता है। |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व की गई छवि को निर्दिष्ट स्ट्रीम में निर्दिष्ट फ़ॉर्मेट में सहेजता है। |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व की गई छवि को निर्दिष्ट एन्कोडर और एन्कोडर पैरामीटर का उपयोग करके निर्दिष्ट फ़ाइल में सहेजता है। |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व की गई छवि को निर्दिष्ट एन्कोडर और एन्कोडर पैरामीटर का उपयोग करके निर्दिष्ट स्ट्रीम में सहेजता है। |
| void [SaveAdd](../image/saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | [Save()](../image/save/) मेथड के पिछले कॉल में निर्दिष्ट फ़ाइल या स्ट्रीम में एक फ्रेम जोड़ता है। |
| void [SaveAdd](../image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | [Save()](../image/save/) मेथड के पिछले कॉल में निर्दिष्ट फ़ाइल या स्ट्रीम में एक फ्रेम जोड़ता है। |
| int [SelectActiveFrame](../image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | निर्दिष्ट फ्रेम चुनता है। |
| void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) override | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व की गई छवि द्वारा उपयोग किए गए रंग पैलेट को सेट करता है। |
| virtual void [set_Tag](../image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | छवि के अतिरिक्त डेटा प्रदान करने वाले ऑब्जेक्ट को सेट करता है। |
| void [SetPixel](./setpixel/)(int, int, [Color](../color/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए बिटमैप छवि में निर्दिष्ट पिक्सेल का रंग सेट करता है। |
| void [SetResolution](./setresolution/)(**float**, **float**) | छवि का रिज़ॉल्यूशन सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | टेम्पलेट के n'th आर्ग्युमेंट को शैर्ड की बजाय वीक्स पॉइंटर सेट करता है। कंटेनरों में पॉइंटर्स को वीक्स मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| void [UnlockBits](./unlockbits/)(const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | निर्दिष्ट बिटमैप को सिस्टम मेमोरी से अनलॉक करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक्स रेफ़रेंस काउंटर को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक्स रेफ़रेंस काउंटर को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## संबंधित देखें

* वर्ग [Image](../image/)
* नेमस्पेस [System::Drawing](../)
* लाइब्रेरी [Aspose.Slides](../../)