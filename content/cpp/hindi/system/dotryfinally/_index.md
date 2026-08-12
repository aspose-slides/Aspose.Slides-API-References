---
title: DoTryFinally()
second_title: Aspose.Slides for C++ एपीआई संदर्भ
description: यह एकल फ़ंक्शन है जो C# के try[-catch]-finally कथन के व्यवहार की नकल करता है। C# के try[-catch]-finally कथन के अनुवाद के दौरान, जब अनुवादकर्ता विकल्प finally_statement_as_lambda को true पर सेट किया जाता है, तो इस कथन को इस मेथड के आवरण में अनुवादित किया जाता है।
type: docs
weight: 2445
url: /hi/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) फ़ंक्शन


C# के try[-catch]-finally कथन के व्यवहार की नकल करने वाला एकमात्र फ़ंक्शन। जब अनुवाद के दौरान अनुवादकर्ता विकल्प finally_statement_as_lambda को true पर सेट किया जाता है, तो कथन को इस मेथड के कॉल में अनुवादित किया जाता है।

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | उस फ़ंक्शन ऑब्जेक्ट का प्रकार जो अनुकरण किए जा रहे try[-catch]-finally कथन के try[-catch] भाग को लागू करता है |
| F | उस फ़ंक्शन ऑब्जेक्ट का प्रकार जो अनुकरण किए जा रहे try[-catch]-finally कथन के finally भाग को लागू करता है |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tryBlock | T\&& | फ़ंक्शन ऑब्जेक्ट जिसका बॉडी अनुकरण किए जा रहे try[-catch]-finally कथन के try[-catch] भाग के कार्यान्वयन को सम्मिलित करता है |
| finallyBlock | F\&& | फ़ंक्शन ऑब्जेक्ट जिसका बॉडी अनुकरण किए जा रहे try[-catch]-finally कथन के finally भाग के कार्यान्वयन को सम्मिलित करता है |

## System::DoTryFinally(T\&&, F\&&) फ़ंक्शन


C# के try[-catch]-finally कथन के व्यवहार की नकल करने वाला एकमात्र फ़ंक्शन। जब अनुवाद के दौरान अनुवादकर्ता विकल्प finally_statement_as_lambda को true पर सेट किया जाता है, तो कथन को इस मेथड के कॉल में अनुवादित किया जाता है। यह ओवरलोड उस स्थिति को संभालता है जहाँ try[-catch]-finally कथन के try[-catch] भाग को लागू करने वाले फ़ंक्शन ऑब्जेक्ट का रिटर्न वैल्यू bool है।

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | उस फ़ंक्शन ऑब्जेक्ट का प्रकार जो अनुकरण किए जा रहे try[-catch]-finally कथन के try[-catch] भाग को लागू करता है |
| F | उस फ़ंक्शन ऑब्जेक्ट का प्रकार जो अनुकरण किए जा रहे try[-catch]-finally कथन के finally भाग को लागू करता है |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tryBlock | T\&& | फ़ंक्शन ऑब्जेक्ट जिसका बॉडी अनुकरण किए जा रहे try[-catch]-finally कथन के try[-catch] भाग के कार्यान्वयन को सम्मिलित करता है |
| finallyBlock | F\&& | फ़ंक्शन ऑब्जेक्ट जिसका बॉडी अनुकरण किए जा रहे try[-catch]-finally कथन के finally भाग के कार्यान्वयन को सम्मिलित करता है |

## System::DoTryFinally(T\&&, F\&&) फ़ंक्शन


C# के try[-catch]-finally कथन के व्यवहार की नकल करने वाला एकमात्र फ़ंक्शन। जब अनुवाद के दौरान अनुवादकर्ता विकल्प finally_statement_as_lambda को true पर सेट किया जाता है, तो कथन को इस मेथड के कॉल में अनुवादित किया जाता है। यह ओवरलोड उस स्थिति को संभालता है जहाँ try[-catch]-finally कथन के try[-catch] भाग को लागू करने वाले फ़ंक्शन ऑब्जेक्ट का रिटर्न वैल्यू bool& है।

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | उस फ़ंक्शन ऑब्जेक्ट का प्रकार जो अनुकरण किए जा रहे try[-catch]-finally कथन के try[-catch] भाग को लागू करता है |
| F | उस फ़ंक्शन ऑब्जेक्ट का प्रकार जो अनुकरण किए जा रहे try[-catch]-finally कथन के finally भाग को लागू करता है |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tryBlock | T\&& | फ़ंक्शन ऑब्जेक्ट जिसका बॉडी अनुकरण किए जा रहे try[-catch]-finally कथन के try[-catch] भाग के कार्यान्वयन को सम्मिलित करता है |
| finallyBlock | F\&& | फ़ंक्शन ऑब्जेक्ट जिसका बॉडी अनुकरण किए जा रहे try[-catch]-finally कथन के finally भाग के कार्यान्वयन को सम्मिलित करता है |

## देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)