---
title: Array
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक क्लास जो एक एरे डेटा संरचना को दर्शाती है। इस क्लास की वस्तुओं को केवल System::MakeArray() और System::MakeObject() फ़ंक्शनों का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार के इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ हो सकती हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों में तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 14
url: /hi/system/array/
---
## Array क्लास

Class that represents an array data structure. Objects of this class should only be allocated using [System::MakeArray()](../makearray/) and [System::MakeObject()](../makeobject/) functions. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | एरे के तत्वों का प्रकार |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| void [Add](./add/)(const T\&) override | समर्थित नहीं है क्योंकि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया एरे केवल-पढ़ने योग्य है। |
|  [Array](./array/)() | एक खाली एरे बनाता है। |
|  [Array](./array/)(int, const T\&) | फ़िलिंग कंस्ट्रक्टर। |
|  [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | फ़िलिंग कंस्ट्रक्टर। |
|  [Array](./array/)(int, const T) | फ़िलिंग कंस्ट्रक्टर। |
|  [Array](./array/)(**vector_t**\&&) | मूव कंस्ट्रक्टर। |
|  [Array](./array/)(const **vector_t**\&) | कॉपी कंस्ट्रक्टर। |
|  [Array](./array/)(const std::vector\<Q\>\&) | एक [Array](./) ऑब्जेक्ट बनाता है और इसे उन मानों से भरता है जो std::vector ऑब्जेक्ट से कॉपी किए गए हैं, जिनका प्रकार **T** के समान है लेकिन **UnderlyingType** से अलग है। |
|  [Array](./array/)(std::vector\<Q\>\&&) | एक [Array](./) ऑब्जेक्ट बनाता है और इसे उन मानों से भरता है जो std::vector ऑब्जेक्ट से मूव किए गए हैं, जिनका प्रकार **T** के समान है लेकिन **UnderlyingType** से अलग है। |
|  [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | एक [Array](./) ऑब्जेक्ट बनाता है और इसे निर्दिष्ट initializer list से मानों से भरता है जिसमें **UnderlyingType** प्रकार के तत्व होते हैं। |
|  [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>\&) | एक [Array](./) ऑब्जेक्ट बनाता है और इसे निर्दिष्ट array से मानों से भरता है जिसमें **UnderlyingType** प्रकार के तत्व होते हैं। |
|  [Array](./array/)(std::initializer_list\<**bool**\>, int) | एक [Array](./) ऑब्जेक्ट बनाता है और इसे निर्दिष्ट initializer list से मानों से भरता है जिसमें **bool** प्रकार के तत्व होते हैं। |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | एरे को केवल-पढ़ने योग्य संग्रह में कास्ट करता है। |
| [iterator](./iterator/) [begin](./begin/)() | कंटेनर के पहले तत्व के लिए एक इटररेटर लौटाता है। यदि कंटेनर खाली है, तो लौटाया गया इटररेटर [end()](./end/) के बराबर होगा। |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | कॉन्स्ट-क्वालिफ़ायर्ड कंटेनर के पहले तत्व के लिए एक इटररेटर लौटाता है। यदि कंटेनर खाली है, तो लौटाया गया इटररेटर [end()](./end/) के बराबर होगा। |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T\&) | सॉर्टेड एरे में बाइनरी सर्च करता है। |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y\&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | असम्पन्न। |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | कंटेनर के पहले कॉन्स्ट-क्वालिफ़ाइड तत्व के लिए एक इटररेटर लौटाता है। यदि कंटेनर खाली है, तो लौटाया गया इटररेटर [cend()](./cend/) के बराबर होगा। |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | कंटेनर के अंतिम तत्व के बाद वाले तत्व के लिए एक इटररेटर लौटाता है। यह तत्व एक प्लेसहोल्डर के रूप में कार्य करता है; इसे एक्सेस करने का प्रयास अनिर्धारित व्यवहार का कारण बनता है। |
| void [Clear](./clear/)() override | समर्थित नहीं है क्योंकि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया एरे केवल-पढ़ने योग्य है। |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | निर्दिष्ट एरे में **startIndex** इंडेक्स से शुरू करके **count** मानों को डिफ़ॉल्ट मानों से प्रतिस्थापित करता है। |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | एरे की क्लोन बनाता है। |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | निर्दिष्ट स्रोत से शुरू करके एक [System.Array](./) के एक रेंज के तत्वों की प्रतिलिपि बनाता है। |
| **bool** [Contains](./contains/)(const T\&) const override | निर्धारित करता है कि निर्दिष्ट आइटम एरे में है या नहीं। |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | एक नया [Array](./) ऑब्जेक्ट बनाता है और इसे निर्दिष्ट एरे के तत्वों से भरता है, जो निर्दिष्ट कनवर्टर डेलीगेट का उपयोग करके **OutputType** प्रकार में परिवर्तित किए गए हैं। |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)>) | एक नया [Array](./) ऑब्जेक्ट बनाता है और इसे निर्दिष्ट एरे के तत्वों से भरता है, जो निर्दिष्ट कनवर्टर फ़ंक्शन ऑब्जेक्ट का उपयोग करके **OutputType** प्रकार में परिवर्तित किए गए हैं। |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | निर्दिष्ट संख्या में तत्वों को स्रोत एरे से गंतव्य एरे में कॉपी करता है। |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | निर्दिष्ट संख्या में तत्वों को स्रोत एरे व्यू से गंतव्य एरे में कॉपी करता है। |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | निर्दिष्ट संख्या में तत्वों को स्रोत एरे से गंतव्य एरे व्यू में कॉपी करता है। |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | निर्दिष्ट संख्या में तत्वों को स्रोत एरे व्यू से गंतव्य एरे व्यू में कॉपी करता है। |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | निर्दिष्ट संख्या में तत्वों को स्टैक पर स्रोत एरे से गंतव्य एरे में कॉपी करता है। |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | स्रोत एरे से गंतव्य स्टैक एरे में निर्दिष्ट संख्या में तत्वों को कॉपी करता है। |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | स्टैक पर स्रोत एरे से स्टैक पर गंतव्य एरे में निर्दिष्ट संख्या में तत्वों को कॉपी करता है। |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | स्रोत एरे से निर्दिष्ट इंडेक्स से शुरू करके निर्दिष्ट संख्या में तत्वों को गंतव्य एरे में निर्दिष्ट स्थान पर कॉपी करता है। |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | स्रोत एरे व्यू से निर्दिष्ट इंडेक्स से शुरू करके निर्दिष्ट संख्या में तत्वों को गंतव्य एरे में निर्दिष्ट स्थान पर कॉपी करता है। |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | स्रोत एरे से निर्दिष्ट इंडेक्स से शुरू करके निर्दिष्ट संख्या में तत्वों को गंतव्य एरे व्यू में निर्दिष्ट स्थान पर कॉपी करता है। |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | स्रोत एरे व्यू से निर्दिष्ट इंडेक्स से शुरू करके निर्दिष्ट संख्या में तत्वों को गंतव्य एरे व्यू में निर्दिष्ट स्थान पर कॉपी करता है। |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | स्टैक पर स्रोत एरे से निर्दिष्ट इंडेक्स से शुरू करके निर्दिष्ट संख्या में तत्वों को गंतव्य एरे में निर्दिष्ट स्थान पर कॉपी करता है। |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | स्रोत एरे से निर्दिष्ट इंडेक्स से शुरू करके निर्दिष्ट संख्या में तत्वों को स्टैक पर गंतव्य एरे में निर्दिष्ट स्थान पर कॉपी करता है। |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | स्टैक पर स्रोत एरे से निर्दिष्ट इंडेक्स से शुरू करके निर्दिष्ट संख्या में तत्वों को स्टैक पर गंतव्य एरे में निर्दिष्ट स्थान पर कॉपी करता है। |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | स्रोत एरे व्यू से निर्दिष्ट इंडेक्स से शुरू करके निर्दिष्ट संख्या में तत्वों को स्टैक पर गंतव्य एरे में निर्दिष्ट स्थान पर कॉपी करता है। |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | वर्तमान एरे के सभी तत्वों को निर्दिष्ट गंतव्य एरे में कॉपी करता है। तत्व गंतव्य एरे में **arrayIndex** तर्क द्वारा निर्दिष्ट इंडेक्स से शुरू होकर डाले जाते हैं। |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | वर्तमान एरे के सभी तत्वों को निर्दिष्ट गंतव्य एरे में कॉपी करता है। तत्व गंतव्य एरे में **dstIndex** तर्क द्वारा निर्दिष्ट इंडेक्स से शुरू होकर डाले जाते हैं। |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | वर्तमान एरे के सभी तत्वों को निर्दिष्ट गंतव्य एरे व्यू में कॉपी करता है। तत्व गंतव्य एरे व्यू में **dstIndex** तर्क द्वारा निर्दिष्ट इंडेक्स से शुरू होकर डाले जाते हैं। |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | वर्तमान एरे से निर्दिष्ट स्थिति से शुरू करके निर्दिष्ट संख्या में तत्वों को निर्दिष्ट गंतव्य एरे में कॉपी करता है। तत्व गंतव्य एरे में **dstIndex** तर्क द्वारा निर्दिष्ट इंडेक्स से शुरू होकर डाले जाते हैं। |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | वर्तमान एरे से निर्दिष्ट स्थिति से शुरू करके निर्दिष्ट संख्या में तत्वों को निर्दिष्ट गंतव्य एरे व्यू में कॉपी करता है। तत्व गंतव्य एरे व्यू में **dstIndex** तर्क द्वारा निर्दिष्ट इंडेक्स से शुरू होकर डाले जाते हैं। |
| int [Count](./count/)() const | एक संख्या लौटाता है जो एरे के सभी आयामों में सभी तत्वों की कुल संख्या को दर्शाती है। |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | रिवर्स्ड कंटेनर के पहले तत्व के लिए एक रिवर्स इटररेटर लौटाता है। यह नॉन-रिवर्स्ड कंटेनर के अंतिम तत्व के बराबर है। यदि कंटेनर खाली है, तो लौटाया गया इटररेटर [crend()](./crend/) के बराबर होता है। |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | रिवर्स्ड कंटेनर के अंतिम तत्व के बाद वाले तत्व के लिए एक रिवर्स इटररेटर लौटाता है। यह नॉन-रिवर्स्ड कंटेनर के पहले तत्व से पहले वाले तत्व के बराबर है। यह तत्व एक प्लेसहोल्डर के रूप में कार्य करता है, इसे एक्सेस करने का प्रयास अनिर्धारित व्यवहार का कारण बनता है। |
| **vector_t**\& [data](./data/)() | एरे तत्वों को संग्रहीत करने के लिए आंतरिक डेटा संरचना का संदर्भ लौटाता है। |
| const **vector_t**\& [data](./data/)() const | एरे तत्वों को संग्रहीत करने के लिए आंतरिक डेटा संरचना का कॉन्स्टेंट संदर्भ लौटाता है। |
| vector_t::pointer [data_ptr](./data_ptr/)() | ऐरे तत्वों के संग्रहीत होने वाले मेमोरी बफ़र की शुरुआत का रॉ पॉइंटर लौटाता है। |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | ऐरे तत्वों के संग्रहीत होने वाले मेमोरी बफ़र की शुरुआत का कॉन्स्टेंट रॉ पॉइंटर लौटाता है। |
| [iterator](./iterator/) [end](./end/)() | कंटेनर के अंतिम तत्व के बाद वाले तत्व के लिए एक इटररेटर लौटाता है। यह तत्व एक प्लेसहोल्डर के रूप में कार्य करता है; इसे एक्सेस करने का प्रयास अनिर्धारित व्यवहार का कारण बनता है। |
| [const_iterator](./const_iterator/) [end](./end/)() const | कॉन्स्ट-क्वालिफ़ाइड कंटेनर के अंतिम तत्व के बाद वाले तत्व के लिए एक इटररेटर लौटाता है। यह तत्व एक प्लेसहोल्डर के रूप में कार्य करता है; इसे एक्सेस करने का प्रयास अनिर्धारित व्यवहार का कारण बनता है। |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../object/equals/) सिमैंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ़्लोटिंग प्वाइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | निर्धारित करता है कि निर्दिष्ट [Array](./) वस्तु में कोई तत्व है जो निर्दिष्ट प्रेडिकेट की आवश्यकताओं को पूरा करता है। |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | निर्दिष्ट ऐरे में पहला तत्व खोजता है जो निर्दिष्ट प्रेडिकेट की शर्तों को पूरा करता है। |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | सभी उन तत्वों को पुनः प्राप्त करता है जो निर्दिष्ट प्रेडिकेट द्वारा परिभाषित शर्तों से मेल खाते हैं। |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | निर्दिष्ट ऐरे में पहला तत्व खोजता है जो निर्दिष्ट प्रेडिकेट की शर्तों को पूरा करता है। |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | निर्दिष्ट ऐरे के प्रत्येक तत्व पर निर्दिष्ट कार्रवाई निष्पादित करता है। |
| int [get_Count](./get_count/)() const override | ऐरे का आकार लौटाता है। |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | जाँचता है कि संग्रह स्थिर आकार का है या नहीं। |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | निर्दिष्ट करता है कि ऐरे केवल-पढ़ने योग्य है या नहीं। |
| **int32_t** [get_Length](./get_length/)() const override | ऐरे के सभी आयामों में सभी तत्वों की कुल संख्या को दर्शाने वाला 32-बिट पूर्णांक लौटाता है। |
| **int64_t** [get_LongLength](./get_longlength/)() const | ऐरे के सभी आयामों में सभी तत्वों की कुल संख्या को दर्शाने वाला 64-बिट पूर्णांक लौटाता है। |
| **int32_t** [get_Rank](./get_rank/)() const | कार्यान्वित नहीं किया गया। |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | वह वस्तु प्राप्त करता है जिसके माध्यम से संग्रह समकालिक किया जाता है। |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | वस्तु से सम्बंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | **Enumerator** वस्तु का पॉइंटर लौटाता है जो वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए ऐरे के तत्वों को IEnumerator इंटरफ़ेस प्रदान करता है। |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) मेथड का समानांतर। कस्टम वस्तुओं की हैशिंग सक्षम करता है। |
| int [GetLength](./getlength/)(int) | निर्दिष्ट आयाम में तत्वों की संख्या लौटाता है। |
| **int64_t** [GetLongLength](./getlonglength/)(int) | निर्दिष्ट आयाम में तत्वों की संख्या को 64-बिट पूर्णांक के रूप में लौटाता है। |
| int [GetLowerBound](./getlowerbound/)(int) const | निर्दिष्ट आयाम की निचली सीमा लौटाता है। |
| size_t [GetSizeTLength](./getsizetlength/)() const | ऐरे के सभी आयामों में सभी तत्वों की कुल संख्या को दर्शाने वाला std::size_t चर लौटाता है। |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../object/gettype/) कॉल का समानांतर। |
| int [GetUpperBound](./getupperbound/)(int) | निर्दिष्ट आयाम की ऊपरी सीमा लौटाता है। |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | कॉपी कंस्ट्रक्टर। |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | मूव कंस्ट्रक्टर। |
| T [idx_get](./idx_get/)(int) const override | निर्दिष्ट इंडेक्स पर आइटम लौटाता है। |
| void [idx_set](./idx_set/)(int, T) override | निर्दिष्ट मान को निर्दिष्ट इंडेक्स पर ऐरे के आइटम के रूप में सेट करता है। |
| int [IndexOf](./indexof/)(const T\&) const override | ऐरे में निर्दिष्ट आइटम की पहली उपस्थिति का सूचकांक निर्धारित करता है। |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | ऐरे में निर्दिष्ट आइटम की पहली उपस्थिति का सूचकांक निर्धारित करता है। |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | निर्दिष्ट इंडेक्स से शुरू करके ऐरे में निर्दिष्ट आइटम की पहली उपस्थिति का सूचकांक निर्धारित करता है। |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | शुरुआती इंडेक्स और रेंज में तत्वों की संख्या द्वारा निर्दिष्ट रेंज में ऐरे के तत्वों में निर्दिष्ट आइटम की पहली उपस्थिति का सूचकांक निर्धारित करता है। |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए ऐरे को निर्दिष्ट ऐरे से मानों से भरता है। |
| void [Initialize](./initialize/)() | ऐरे को प्रकार **T** के डिफ़ॉल्ट निर्मित वस्तुओं से भरता है। |
| void [Insert](./insert/)(int, const T\&) override | समर्थित नहीं है क्योंकि वर्तमान वस्तु द्वारा प्रतिनिधित्व किया गया ऐरे केवल-पढ़ने योग्य है। |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | जाँचें कि वस्तु targetType द्वारा वर्णित प्रकार की एक उदाहरण का प्रतिनिधित्व करती है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | शुरुआती इंडेक्स और रेंज में तत्वों की संख्या द्वारा निर्दिष्ट रेंज में ऐरे के तत्वों में निर्दिष्ट आइटम की अंतिम उपस्थिति का सूचकांक निर्धारित करता है। |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | निर्दिष्ट इंडेक्स से शुरू करके ऐरे में निर्दिष्ट आइटम की अंतिम उपस्थिति का सूचकांक निर्धारित करता है। |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | ऐरे में निर्दिष्ट आइटम की अंतिम उपस्थिति का सूचकांक निर्धारित करता है। |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | एक अनुक्रम पर संचयक फ़ंक्शन लागू करता है। |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | जाँचता है कि क्या अनुक्रम के सभी तत्व एक शर्त को संतुष्ट करते हैं। |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | जाँचता है कि अनुक्रम में कोई तत्व हैं या नहीं। |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | जाँचता है कि अनुक्रम का कोई भी तत्व मौजूद है या शर्त को संतुष्ट करता है। |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | संख्यात्मक मानों के अनुक्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<T, ResultType\>\&) | इनपुट अनुक्रम के प्रत्येक तत्व पर एक ट्रांसफ़ॉर्म फ़ंक्शन को लागू करके प्राप्त मानों के अनुक्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | तत्वों को निर्दिष्ट प्रकार में कास्ट करता है। |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | दो अनुक्रमों को संयोजित करता है। |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | जाँचता है कि अनुक्रम में निर्दिष्ट मान है या नहीं। |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | अनुक्रम में तत्वों की संख्या लौटाता है (प्रत्यक्ष गिनती द्वारा गणना किया गया)। |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | अनुक्रम में उन तत्वों की संख्या लौटाता है जो निर्दिष्ट शर्त को संतुष्ट करते हैं। |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | अनुक्रम में निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | अनुक्रम में निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | अनुक्रम का पहला तत्व लौटाता है। |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | निर्दिष्ट शर्त को संतुष्ट करने वाला अनुक्रम का पहला तत्व लौटाता है। |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | अनुक्रम का पहला तत्व लौटाता है, या यदि अनुक्रम खाली है तो डिफ़ॉल्ट मान लौटाता है। |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | शर्त को संतुष्ट करने वाला अनुक्रम का पहला तत्व लौटाता है या यदि ऐसा कोई तत्व नहीं मिला तो डिफ़ॉल्ट मान लौटाता है। |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | एक अनुक्रम के तत्वों को समूहित करता है। |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | एक अनुक्रम के तत्वों को समूहित करता है। |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | अनुक्रम का अंतिम तत्व लौटाता है। |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | अनुक्रम का अंतिम तत्व लौटाता है, या यदि अनुक्रम खाली है तो डिफ़ॉल्ट मान लौटाता है। |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | एक सामान्य अनुक्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन को लागू करता है और अधिकतम परिणामी मान लौटाता है। |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | एक सामान्य अनुक्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन को लागू करता है और न्यूनतम परिणामी मान लौटाता है। |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | निर्दिष्ट प्रकार के आधार पर अनुक्रम के तत्वों को फ़िल्टर करता है। |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | keySelector द्वारा चुनी गई कुंजी मूल्यों के अनुसार अनुक्रम के तत्वों को आरोही क्रम में सॉर्ट करता है। |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | keySelector द्वारा चुनी गई कुंजी मूल्यों के अनुसार अनुक्रम के तत्वों को अवरोही क्रम में सॉर्ट करता है। |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | एक अनुक्रम में तत्वों का क्रम उलट देता है। |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | एक अनुक्रम के तत्वों को परिवर्तित करता है। |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | एक अनुक्रम के प्रत्येक तत्व को उसके इंडेक्स को शामिल करके नई रूप में परिवर्तित करता है। |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | एक अनुक्रम के प्रत्येक तत्व को प्रोजेक्ट करता है और परिणामी अनुक्रमों को एक ही अनुक्रम में मिलाता है। |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | एक अनुक्रम की शुरुआत से निर्दिष्ट संख्या में निरंतर तत्वों को छोड़ता है और शेष लौटाता है। |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | एक अनुक्रम की शुरुआत से निर्दिष्ट संख्या में निरंतर तत्वों को लौटाता है। |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | एक अनुक्रम से ऐरे बनाता है। |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | एक अनुक्रम से List<T> बनाता है। |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | निर्दिष्ट प्रेडिकेट के आधार पर एक अनुक्रम को फ़िल्टर करता है। |
| void [Lock](../object/lock/)() | C# lock() कथन को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री वस्तु का उपयोग करें। |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | [operator<()](../operator_less/) का उपयोग करके तत्वों की तुलना करते हुए ऐरे में सबसे बड़ा तत्व खोजता है। |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | [operator<()](../operator_less/) का उपयोग करके तत्वों की तुलना करते हुए ऐरे में सबसे छोटा तत्व खोजता है। |
|  [Object](../object/object/)() | वस्तु बनाता है। सभी आंतरिक डेटा संरचनाओं को आरंभ करता है। |
|  [Object](../object/object/)([Object](../object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया वस्तु प्रारंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया वस्तु प्रारंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | मूव असाइनमेंट ऑपरेटर। |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | मूव असाइनमेंट ऑपरेटर। |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | निर्दिष्ट इंडेक्स पर एक आइटम लौटाता है। |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | निर्दिष्ट इंडेक्स पर एक आइटम लौटाता है। |
| void * [raw_data_ptr](./raw_data_ptr/)() override | सिंगल-डायमेंशन ऐरे के पहले तत्व के पॉइंटर को लौटाता है। मल्टी-डायमेंशन ऐरे के लिए परिणाम अपरिभाषित है। |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | रिवर्स्ड कंटेनर के पहले तत्व के लिए एक रिवर्स इटेरेटर लौटाता है। यह नॉन-रिवर्स्ड कंटेनर के अंतिम तत्व के अनुरूप है। यदि कंटेनर खाली है, तो लौटाया गया इटेरेटर [rend()](./rend/) के बराबर होता है। |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | रिवर्स कंटेनर के पहले तत्व के लिए एक रिवर्स इटररेटर लौटाता है। यह गैर-रिवर्स्ड कंटेनर के अंतिम तत्व के अनुरूप है। यदि कंटेनर खाली है, तो लौटाए गए इटररेटर का मान [rend()](./rend/) के बराबर होता है। |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | निल पॉइंटर के साथ मान प्रकार वस्तु की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../object/referenceequals/) का विशेषीकरण। |
| **bool** [Remove](./remove/)(const T\&) override | समर्थित नहीं है क्योंकि वर्तमान वस्तु द्वारा दर्शाए गए एरे को केवल-पढ़ने योग्य माना गया है। |
| void [RemoveAt](./removeat/)(int) override | समर्थित नहीं है क्योंकि वर्तमान वस्तु द्वारा दर्शाए गए एरे को केवल-पढ़ने योग्य माना गया है। |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट घटाता है। |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | रिवर्स कंटेनर के अंतिम तत्व के बाद के तत्व के लिए एक रिवर्स इटररेटर लौटाता है। यह गैर-रिवर्स्ड कंटेनर के पहले तत्व से पहले वाले तत्व के अनुरूप है। यह तत्व एक प्लेसहोल्डर के रूप में कार्य करता है, इसे एक्सेस करने का प्रयास अनिर्धारित व्यवहार का परिणाम देता है। |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | रिवर्स कंटेनर के अंतिम तत्व के बाद के तत्व के लिए एक रिवर्स इटररेटर लौटाता है। यह गैर-रिवर्स्ड कंटेनर के पहले तत्व से पहले वाले तत्व के अनुरूप है। यह तत्व एक प्लेसहोल्डर के रूप में कार्य करता है, इसे एक्सेस करने का प्रयास अनिर्धारित व्यवहार का परिणाम देता है। |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int) | निर्दिष्ट एरे का आकार निर्दिष्ट मान में बदलता है या निर्दिष्ट आकार के साथ नया एरे बनाता है। |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | निर्दिष्ट एरे में तत्वों को उलटता है। |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | निर्दिष्ट एरे में तत्वों की एक रेंज को उलटता है। |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | एरे को संग्रहीत पॉइंटर्स को न्यूनतम (weak) मानने के लिए सेट करता है (यदि लागू हो)। |
| void [SetValue](./setvalue/)(const T\&, int) | निर्दिष्ट इंडेक्स पर तत्व का मान सेट करता है। |
| int [SharedCount](../object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | डिफ़ॉल्ट comparer का उपयोग करके निर्दिष्ट एरे में तत्वों को क्रमबद्ध करता है। |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | डिफ़ॉल्ट comparer का उपयोग करके निर्दिष्ट एरे में तत्वों की एक रेंज को क्रमबद्ध करता है। |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | निर्दिष्ट comparer का उपयोग करके निर्दिष्ट एरे में तत्वों को क्रमबद्ध करता है। |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Y\>\>\&) | लागू नहीं किया गया। |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [System::Comparison](../comparison/)\<T\>\&) | निर्दिष्ट तुलना का उपयोग करके निर्दिष्ट एरे में तत्वों को क्रमबद्ध करता है। |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&) | दो एरे को क्रमबद्ध करता है, एक में कुंजियाँ और दूसरा – संबंधित आइटम्स, कुंजियों वाले एरे के मूल्यों के आधार पर, जिनके तत्वों की तुलना operator< से की जाती है। |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&, int, int) | दो एरे को क्रमबद्ध करता है, एक में कुंजियाँ और दूसरा – संबंधित आइटम्स, कुंजियों वाले एरे के मूल्यों के आधार पर, जिनके तत्वों की तुलना डिफ़ॉल्ट comparer से की जाती है। |
| virtual [String](../string/) [ToString](../object/tostring/)() const | C# [Object.ToString()](../object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट को स्ट्रिंग में बदलने की सुविधा देता है। |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | निर्धारित करता है कि क्या निर्दिष्ट एरे में सभी तत्व निर्दिष्ट प्रेडिकेट द्वारा परिभाषित शर्तों को पूरा करते हैं। |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) संरचना को लागू करता है। |
| void [Unlock](../object/unlock/)() | C# lock() स्टेटमेंट के अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | वर्तमान कंटेनर के लिए begin const इटररेटर की इम्प्लीमेंटेशन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | वर्तमान कंटेनर के लिए begin इटररेटर की इम्प्लीमेंटेशन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | वर्तमान कंटेनर के लिए end const इटररेटर की इम्प्लीमेंटेशन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | वर्तमान कंटेनर के लिए end इटररेटर की इम्प्लीमेंटेशन प्राप्त करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | विनाशकर्ता। |
| virtual  [~Object](../object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [ValueType](./valuetype/) | एरे के तत्वों के प्रकार का उपनाम। |
| [UnderlyingType](./underlyingtype/) | एरे के प्रत्येक तत्व को दर्शाने के लिए उपयोग किए जाने वाले प्रकार का उपनाम। |
| [EnumerablePtr](./enumerableptr/) | IEnumerable ऑब्जेक्ट की ओर इशारा करने वाले shared pointer प्रकार का उपनाम, जिसमें **T** प्रकार के तत्व होते हैं। |
| [EnumeratorPtr](./enumeratorptr/) | IEnumerator ऑब्जेक्ट की ओर इशारा करने वाले shared pointer प्रकार का उपनाम, जिसमें **T** प्रकार के तत्व होते हैं। |
| [iterator](./iterator/) | इटररेटर प्रकार। |
| [const_iterator](./const_iterator/) | कॉन्स्ट इटररेटर प्रकार। |
| [reverse_iterator](./reverse_iterator/) | रिवर्स इटररेटर प्रकार। |
| [const_reverse_iterator](./const_reverse_iterator/) | कॉन्स्ट रिवर्स इटररेटर प्रकार। |

## टिप्पणी



```cpp
#include <system/array.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<Array<int32_t>> &arrayPtr)
{
  for (auto item: arrayPtr)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // एरे बनाएं और भरें।
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // एरे के आइटम प्रिंट करें।
  Print(arrayPtr);

  // एरे के आइटम को आरोही क्रम में सॉर्ट करें।
  Array<int32_t>::Sort(arrayPtr);

  // एरे के आइटम प्रिंट करें।
  Print(arrayPtr);

  // एरे के आइटमों की गिनती प्रिंट करें।
  std::cout << arrayPtr->get_Length() << std::endl;

  // उस आइटम का इंडेक्स प्रिंट करें जो 4 के बराबर है।
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // एरे का आकार बदलें।
  Array<int32_t>::Resize(arrayPtr, 3);

  // एरे के आइटम प्रिंट करें।
  Print(arrayPtr);

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## संबंधित देखें

* क्लास [ArrayBase](../arraybase/)
* क्लास [IList](../../system.collections.generic/ilist/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)