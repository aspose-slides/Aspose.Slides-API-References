---
title: Math
second_title: Aspose.Slides for C++ API संदर्भ
description: गणितीय फ़ंक्शन शामिल करता है। यह एक स्थैतिक प्रकार है जिसके पास कोई इंस्टेंस सेवाएँ नहीं हैं। आपको किसी भी माध्यम से इसके इंस्टेंस कभी नहीं बनाने चाहिए।
type: docs
weight: 1782
url: /hi/system/math/
---
## Math संरचना

Contains math functions. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Math
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static T [Abs](./abs/)(T) | निर्दिष्ट मान का निरपेक्ष मान लौटाता है। |
| static [Decimal](../decimal/) [Abs](./abs/)(const [Decimal](../decimal/)\&) | निर्दिष्ट [Decimal](../decimal/) वस्तु द्वारा प्रतिनिधित्व किए गए मान का निरपेक्ष मान लौटाता है। |
| static **double** [Acos](./acos/)(**double**) | निर्दिष्ट मान का arccosine गणना करता है। |
| static **double** [Asin](./asin/)(**double**) | निर्दिष्ट मान का arcsin गणना करता है। |
| static **double** [Atan](./atan/)(**double**) | निर्दिष्ट मान का arctan गणना करता है। |
| static **double** [Atan2](./atan2/)(**double**, **double**) | निर्दिष्ट मानों के अनुपात का arctan गणना करता है। |
| static **int64_t** [BigMul](./bigmul/)(int, int) | दो 32-बिट पूर्णांक का पूर्ण गुणनफल लौटाता है। |
| static [Decimal](../decimal/) [Ceiling](./ceiling/)(const [Decimal](../decimal/)\&) | निर्दिष्ट मान से बड़ा या बराबर सबसे छोटा पूर्णांक मान लौटाता है। |
| static **double** [Ceiling](./ceiling/)(**double**) | निर्दिष्ट मान से बड़ा या बराबर सबसे छोटा पूर्णांक मान लौटाता है। |
| static **double** [Cos](./cos/)(**double**) | निर्दिष्ट मान का कोसाइन गणना करता है। |
| static **double** [Cosh](./cosh/)(**double**) | निर्दिष्ट मान का हाइपरबोलिक कोसाइन गणना करता है। |
| static int [DivRem](./divrem/)(int, int, int\&) | दो 32-बिट पूर्णांक का भागफल और शेष निकालता है। |
| static **int64_t** [DivRem](./divrem/)(**int64_t**, **int64_t**, **int64_t**\&) | दो 64-बिट पूर्णांक का भागफल और शेष निकालता है। |
| static **double** [Exp](./exp/)(**double**) | निर्दिष्ट घात पर e स्थिरांक का मान लौटाता है। |
| static [Decimal](../decimal/) [Floor](./floor/)(const [Decimal](../decimal/)\&) | निर्दिष्ट मान से छोटा या बराबर सबसे बड़ा पूर्णांक मान लौटाता है। |
| static **double** [Floor](./floor/)(**double**) | निर्दिष्ट मान से छोटा या बराबर सबसे बड़ा पूर्णांक मान लौटाता है। |
| static **double** [IEEERemainder](./ieeeremainder/)(**double**, **double**) | निर्दिष्ट संख्या को दूसरी निर्दिष्ट संख्या से भाग देने पर शेष लौटाता है। |
| static **double** [Log](./log/)(**double**) | निर्दिष्ट मान का प्राकृतिक लघुगणक लौटाता है। |
| static **double** [Log](./log/)(**double**, **double**) | निर्दिष्ट आधार में निर्दिष्ट मान का लघुगणक लौटाता है। |
| static **double** [Log10](./log10/)(**double**) | निर्दिष्ट मान का आधार-10 लघुगणक लौटाता है। |
| static auto [Max](./max/)(T0, T1) | निर्दिष्ट दो संख्यात्मक मानों में से सबसे बड़ा मान लौटाता है। |
| static T0 [Max](./max/)(T0, T1) | निर्दिष्ट दो संख्यात्मक मानों में से सबसे बड़ा मान लौटाता है। |
| **float** [Max_](./max_/)(**float**, **float**) | निर्दिष्ट दो मानों में से सबसे बड़ा सिंगल-प्रिसिशन फ्लोटिंग पॉइंट मान लौटाता है। |
| **double** [Max_](./max_/)(**double**, **double**) | निर्दिष्ट दो मानों में से सबसे बड़ा डबल-प्रिसिशन फ्लोटिंग पॉइंट मान लौटाता है। |
| static auto [Min](./min/)(T0, T1) | निर्दिष्ट दो संख्यात्मक मानों में से सबसे छोटा मान लौटाता है। |
| static T0 [Min](./min/)(T0, T1) | निर्दिष्ट दो संख्यात्मक मानों में से सबसे छोटा मान लौटाता है। |
| **float** [Min_](./min_/)(**float**, **float**) | निर्दिष्ट दो मानों में से सबसे छोटा सिंगल-प्रिसिशन फ्लोटिंग पॉइंट मान लौटाता है। |
| **double** [Min_](./min_/)(**double**, **double**) | निर्दिष्ट दो मानों में से सबसे छोटा डबल-प्रिसिशन फ्लोटिंग पॉइंट मान लौटाता है। |
| static T [Modulus](./modulus/)(T, T) | एक निर्दिष्ट मान को दूसरे निर्दिष्ट मान से भाग देने पर शेष निकालता है। |
| static **double** [Pow](./pow/)(**double**, **double**) | निर्दिष्ट मान को निर्दिष्ट घात तक उठाकर लौटाता है। |
| static **double** [Round](./round/)(**double**) | निर्दिष्ट मान को निकटतम पूर्णांक मान तक गोल करता है। |
| static **double** [Round](./round/)(**double**, int) | निर्दिष्ट मान को निर्दिष्ट दशमलव स्थानों की संख्या के साथ निकटतम मान तक गोल करता है। |
| static **double** [Round](./round/)(**double**, [MidpointRounding](../midpointrounding/)) | निर्दिष्ट मान को निकटतम पूर्णांक संख्या तक गोल करता है। एक पैरामीटर निर्धारित करता है कि जब मान दो निकटतम संख्याओं के बराबर दूरी पर हो तो फ़ंक्शन का व्यवहार क्या होगा। |
| static **double** [Round](./round/)(**double**, int, [MidpointRounding](../midpointrounding/)) | निर्दिष्ट मान को निर्दिष्ट दशमलव स्थानों की संख्या के साथ निकटतम मान तक गोल करता है। एक पैरामीटर निर्धारित करता है कि जब मान दो निकटतम संख्याओं के बराबर दूरी पर हो तो फ़ंक्शन का व्यवहार क्या होगा। |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&) | निर्दिष्ट मान को निकटतम पूर्णांक मान तक गोल करता है। |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int) | निर्दिष्ट मान को निर्दिष्ट दशमलव स्थानों की संख्या के साथ निकटतम मान तक गोल करता है। |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, [MidpointRounding](../midpointrounding/)) | निर्दिष्ट मान को निकटतम पूर्णांक संख्या तक गोल करता है। एक पैरामीटर निर्धारित करता है कि जब मान दो निकटतम संख्याओं के बराबर दूरी पर हो तो फ़ंक्शन का व्यवहार क्या होगा। |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int, [MidpointRounding](../midpointrounding/)) | निर्दिष्ट मान को निर्दिष्ट दशमलव स्थानों की संख्या के साथ निकटतम मान तक गोल करता है। एक पैरामीटर निर्धारित करता है कि जब मान दो निकटतम संख्याओं के बराबर दूरी पर हो तो फ़ंक्शन का व्यवहार क्या होगा। |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | निर्दिष्ट साइनड पूर्णांक मान के चिह्न का निर्धारण करता है। |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | निर्दिष्ट फ्लोटिंग-पॉइंट मान के चिह्न का निर्धारण करता है। |
| static int [Sign](./sign/)(const [Decimal](../decimal/)\&) | निर्दिष्ट दशमलव मान के चिह्न का निर्धारण करता है। |
| static **double** [Sin](./sin/)(**double**) | निर्दिष्ट मान का साइन गणना करता है। |
| static **double** [Sinh](./sinh/)(**double**) | निर्दिष्ट मान का हाइपरबोलिक साइन गणना करता है। |
| static **double** [Sqrt](./sqrt/)(**double**) | निर्दिष्ट मान का वर्गमूल लौटाता है। |
| static **double** [Tan](./tan/)(**double**) | निर्दिष्ट मान का टैंजेंट गणना करता है। |
| static **double** [Tanh](./tanh/)(**double**) | निर्दिष्ट मान का हाइपरबोलिक टैंजेंट गणना करता है। |
| static [Decimal](../decimal/) [Truncate](./truncate/)(const [Decimal](../decimal/)\&) | निर्दिष्ट [Decimal](../decimal/) वस्तु द्वारा प्रदर्शित मान के समान पूर्णांक भाग वाला [Decimal](../decimal/) वस्तु लौटाता है, जिसमें सभी दशमलव अंक हटाए गए हैं। |
| static **double** [Truncate](./truncate/)(**double**) | निर्दिष्ट मान के समान पूर्णांक भाग वाला, सभी दशमलव अंक हटाए हुए, डबल-प्रिसिशन फ्लोटिंग पॉइंट मान लौटाता है। |

## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| static [E](./e/) | प्राकृतिक लघुगणक का आधार। |
| static [NaN](./nan/) | Not-a-Number मान को दर्शाता है। |
| static [NegativeInfinity](./negativeinfinity/) | निगेटिव अनंत को दर्शाता है। |
| static [PI](./pi/) | Pi संख्या का स्थिरांक। |
| static [PositiveInfinity](./positiveinfinity/) | पॉज़िटिव अनंत को दर्शाता है। |

## टिप्पणियाँ



```cpp
#include "system/math.h"
#include <iostream>

int main()
{
  using namespace System;

  // निरपेक्ष मानों को प्रिंट करें।
  for (int i = -1; i < 2; ++i)
  {
    std::cout << Math::Abs(i) << " ";
  }
  std::cout << std::endl;

  // PI/2 का साइन और PI का कोसाइन प्रिंट करें।
  std::cout << "sin(PI/2)=" << Math::Sin(Math::PI/2) << "; cos(PI)=" << Math::Cos(Math::PI) << std::endl;

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट देता है:
1 0 1
sin(PI/2)=1; cos(PI)=-1
*/
```

## संबंधित देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)