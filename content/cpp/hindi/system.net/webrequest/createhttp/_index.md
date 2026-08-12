---
title: CreateHttp()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट URI का उपयोग करके WebRequest क्लास का नया उदाहरण बनाता है।
type: docs
weight: 79
url: /hi/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) method

निर्दिष्ट URI का उपयोग करके [WebRequest](../) क्लास की नई एक उदाहरण बनाता है।

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | निर्दिष्ट URI का उपयोग करके [WebRequest](../) क्लास का नया उदाहरण बनाने के लिए उपयोग किया जाता है। |

### रिटर्न वैल्यू

एक नया बनाया गया WebRequest-class उदाहरण।

## टिप्पणी

जब निर्दिष्ट URI किसी भी स्कीम से शुरू होता है सिवाय [http://](http://) या [https://](https://) के, तो NotSupportedException फेंका जाएगा।

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) method

निर्दिष्ट URI का उपयोग करके [WebRequest](../) क्लास की नई एक उदाहरण बनाता है।

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | निर्दिष्ट URI का उपयोग करके [WebRequest](../) क्लास का नया उदाहरण बनाने के लिए उपयोग किया जाता है। |

### रिटर्न वैल्यू

एक नया बनाया गया WebRequest-class उदाहरण।

## टिप्पणी

जब निर्दिष्ट URI किसी भी स्कीम से शुरू होता है सिवाय [http://](http://) या [https://](https://) के, तो NotSupportedException फेंका जाएगा।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [HttpWebRequest](../../httpwebrequest/)
* क्लास [String](../../../system/string/)
* क्लास [WebRequest](../)
* क्लास [Uri](../../../system/uri/)
* नामस्थान [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)