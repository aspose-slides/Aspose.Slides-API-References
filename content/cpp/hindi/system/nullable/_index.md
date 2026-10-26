---
title: Nullable
second_title: Aspose.Slides for C++ API संदर्भ
description: फ़ॉरवर्ड घोषणा।
type: docs
weight: 1106
url: /hi/system/nullable/
---
## नल योग्य क्लास

Forward declaration.

```cpp
template<typename T>class Nullable
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | आधारभूत मान प्रकार जिसे [Nullable](./) क्लास द्वारा विस्तारित किया गया है |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट [Nullable](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान के बराबर है। |
| **bool** [get_HasValue](./get_hasvalue/)() const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट कोई मान प्रतिनिधित्व करता है या नहीं। |
| T [get_Value](./get_value/)() const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान की एक प्रति लौटाता है। |
| int [GetHashCode](./gethashcode/)() const | वर्तमान ऑब्जेक्ट के लिए एक हैश कोड लौटाता है। |
| T [GetValueOrDefault](./getvalueordefault/)(T) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान लौटाता है या यदि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान नल है तो निर्दिष्ट मान लौटाता है। |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट नल-मान दर्शाता है या नहीं। |
|  [Nullable](./nullable/)() | एक इंस्टेंस बनाता है जो नल-मान का प्रतिनिधित्व करता है। |
|  [Nullable](./nullable/)(std::nullptr_t) | एक इंस्टेंस बनाता है जो नल को दर्शाता है। |
|  [Nullable](./nullable/)(const T1\&) | एक [Nullable](./) क्लास का इंस्टेंस बनाता है जो निर्दिष्ट मान को आधारभूत प्रकार T के मान में (यदि आवश्यक हो) परिवर्तित करके दर्शाता है। |
|  [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | एक इंस्टेंस बनाता है जो निर्दिष्ट [Nullable](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान को दर्शाता है। निर्दिष्ट नलिबल ऑब्जेक्ट विभिन्न प्रकार के मान को दर्शा सकता है जिससे बना इंस्टेंस के आधारभूत प्रकार से अलग हो; इस मामले में प्रतिनिधित्व किया गया मान प्रकार T में परिवर्तित हो जाता है। |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | एक सहायक फ़ंक्शन जो जांचता है कि यह और **अन्य** दोनों नल नहीं हैं और यदि ऐसा है तो एक लैम्ब्डा कॉल करता है। कार्यान्वयन में उपयोग किया जाता है। |
|  [operator const T &](./operator_const_t__and/)() const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान का एक स्थायी संदर्भ लौटाता है। |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान नल नहीं है। |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट मान के बराबर नहीं है। |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट [Nullable](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान के बराबर नहीं है। |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | [operator&=()](./operator_and_equal/) को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान पर लागू करता है, जहाँ निर्दिष्ट मान दाएँ पक्ष के तर्क के रूप में उपयोग होता है। |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | Nullable<T> क्लास का डिफ़ॉल्ट निर्मित इंस्टेंस लौटाता है। |
| auto [operator+](./operator_plus/)(const T1\&) const | नलिबल और गैर-नलिबल मानों को जोड़ता है। |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | नलिबल मानों को जोड़ता है। |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | वर्तमान ऑब्जेक्ट को रीसेट करता है ताकि वह नल-मान दर्शाए। |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | [operator+=()](./operator_plus_equal/) को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान पर लागू करता है, जहाँ निर्दिष्ट मान दाएँ पक्ष के तर्क के रूप में उपयोग होता है। |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | [operator+=()](./operator_plus_equal/) को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान पर लागू करता है, जहाँ निर्दिष्ट [Nullable](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान दाएँ पक्ष के तर्क के रूप में उपयोग होता है। |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | नलिबल और नल-संकेतित मानों को घटाता है। |
| auto [operator-](./operator_minus/)(const T1\&) const | नलिबल और गैर-नलिबल मानों को घटाता है। |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | नलिबल मानों को घटाता है। |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | [Nullable](./) क्लास का एक इंस्टेंस लौटाता है जो नल-मान दर्शाता है। |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | [operator-=()](./operator_minus_equal/) को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान पर लागू करता है, जहाँ निर्दिष्ट मान दाएँ पक्ष के तर्क के रूप में उपयोग होता है। |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | [operator-=()](./operator_minus_equal/) को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान पर लागू करता है, जहाँ निर्दिष्ट [Nullable](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान दाएँ पक्ष के तर्क के रूप में उपयोग होता है। |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | हमेशा false लौटाता है। |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान [operator<()](./operator_less/) लागू करके निर्दिष्ट मान से छोटा है। |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान [operator<()](./operator_less/) लागू करके निर्दिष्ट [Nullable](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान से छोटा है। |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | हमेशा false लौटाता है। |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान [operator<=()](./operator_less_equal/) लागू करके निर्दिष्ट मान से कम या बराबर है। |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान [operator<=()](./operator_less_equal/) लागू करके निर्दिष्ट [Nullable](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान से कम या बराबर है। |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | वर्तमान ऑब्जेक्ट को नल असाइन करता है। |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | ऑब्जेक्ट के वर्तमान प्रतिनिधित्व मान को निर्दिष्ट मान से बदलता है। |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | ऑब्जेक्ट के वर्तमान प्रतिनिधित्व मान को निर्दिष्ट मान से बदलता है। |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान नल है। |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट मान के बराबर है। |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट [Nullable](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान के बराबर है। |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | हमेशा false लौटाता है। |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान [operator>()](./operator_greater/) लागू करके निर्दिष्ट मान से बड़ा है। |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान [operator>()](./operator_greater/) लागू करके निर्दिष्ट [Nullable](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान से बड़ा है। |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | हमेशा false लौटाता है। |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान [operator>=()](./operator_greater_equal/) लागू करके निर्दिष्ट ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान से बड़ा या बराबर है। |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान [operator>=()](./operator_greater_equal/) लागू करके निर्दिष्ट [Nullable](./) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान से बड़ा या बराबर है। |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | [operator|=()](./operator_or_equal/) को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान पर लागू करता है, जहाँ निर्दिष्ट मान दाएँ पक्ष के तर्क के रूप में उपयोग होता है। |
| void [reset](./reset/)() | वर्तमान में प्रतिनिधित्व किए गए मान को नल सेट करता है। |
| void [set_Value](./set_value/)(const T\&) | नलिबल ऑब्जेक्ट को नया मान सेट करता है। |
| [String](../string/) [ToString](./tostring/)() const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान को स्ट्रिंग में परिवर्तित करता है। |
## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [ValueType](./valuetype/) | इस क्लास द्वारा प्रतिनिधित्व किए गए मान के प्रकार के लिए एक उपनाम। |
## टिप्पणी

निर्दिष्ट प्रकार का वह मान दर्शाता है जिसे नल असाइन किया जा सकता है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान या रेफ़रेंस द्वारा पास किया जाना चाहिए। इस प्रकार की वस्तुओं को प्रबंधित करने के लिए कभी भी [System::SmartPtr](../smartptr/) क्लास का प्रयोग न करें।

## देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)