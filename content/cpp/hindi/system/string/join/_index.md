---
title: Join()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: स्ट्रिंग को विभाजक के रूप में उपयोग करके एरे को जोड़ता है।
type: docs
weight: 846
url: /hi/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) विधि


स्ट्रिंग को विभाजक के रूप में उपयोग करके एरे को जोड़ता है।

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```


### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) एरे तत्वों के बीच रखने के लिए जब उन्हें जोड़ा जा रहा हो। |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) जोड़ने के लिए भाग। |
| startIndex | int | एरे में पहला इंडेक्स जिससे जोड़ना शुरू होगा। |
| count | int | जोड़ने के लिए एरे तत्वों की संख्या। -1 का अर्थ है 'जब तक एरे समाप्त न हो'। |

### रिटर्न वैल्यू

[String](../) जॉइन किए गए एरे तत्वों को प्रदर्शित करता है।

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) विधि


स्ट्रिंग को विभाजक के रूप में उपयोग करके एरे को जोड़ता है।

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```


### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) एरे तत्वों के बीच रखने के लिए जब उन्हें जोड़ा जा रहा हो। |
| parts | const System::Details::ArrayView\<[String](../)\>\& | जोड़ने के लिए भागों का ArrayView। |
| startIndex | int | एरे में पहला इंडेक्स जिससे जोड़ना शुरू होगा। |
| count | int | जोड़ने के लिए एरे तत्वों की संख्या। -1 का अर्थ है 'जब तक एरे समाप्त न हो'। |

### रिटर्न वैल्यू

[String](../) जॉइन किए गए एरे तत्वों को प्रदर्शित करता है।

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) विधि


स्ट्रिंग को विभाजक के रूप में उपयोग करके एरे को जोड़ता है।

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```


### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) एरे तत्वों के बीच रखने के लिए जब उन्हें जोड़ा जा रहा हो। |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - भागों का एन्यूमेरेबल ऑब्जेक्ट |

### रिटर्न वैल्यू

[String](../) जॉइन किए गए तत्वों को प्रदर्शित करता है।

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) विधि


स्ट्रिंग को विभाजक के रूप में उपयोग करके एरे को जोड़ता है।

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```


### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) एरे तत्वों के बीच रखने के लिए जब उन्हें जोड़ा जा रहा हो। |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) जोड़ने के लिए भाग। |

### रिटर्न वैल्यू

[String](../) जॉइन किए गए तत्वों को प्रदर्शित करता है।

## देखें

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [Object](../../object/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)