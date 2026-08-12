---
title: Uri()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट URI को दर्शाने वाला एक Uri ऑब्जेक्ट बनाता है।
type: docs
weight: 287
url: /hi/system/uri/uri/
---
## Uri::Uri(const String\&) कन्स्ट्रक्टर


निर्दिष्ट URI को प्रदर्शित करने वाला एक [Uri](../) ऑब्जेक्ट बनाता है।

```cpp
System::Uri::Uri(const String &uriString)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | The string URI to be represented by the object being constructed |


## Uri::Uri(const String\&, bool) कन्स्ट्रक्टर


निर्दिष्ट URI को दर्शाने वाला एक [Uri](../) ऑब्जेक्ट बनाता है; एक आर्ग्युमेंट यह निर्धारित करता है कि क्या URI को एस्केप किया जाना चाहिए।

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | The string URI to be represented by the object being constructed |
| dontEscape | **bool** | Specifies if the URI should not be escaped |


## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) कन्स्ट्रक्टर


नियत [Uri](../) ऑब्जेक्ट जो बेस URI को दर्शाता है और सापेक्ष URI की स्ट्रिंग प्रस्तुति से एक [Uri](../) ऑब्जेक्ट बनाता है; एक आर्ग्युमेंट यह निर्धारित करता है कि क्या URI को एस्केप किया जाना चाहिए।

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The base URI |
| relativeUri | const [String](../../string/)\& | The relative URI that is added to the base URI |
| dontEscape | **bool** | Specifies if the URI should not be escaped |


## Uri::Uri(const String\&, UriKind) कन्स्ट्रक्टर


निर्दिष्ट URI को दर्शाने वाला एक [Uri](../) ऑब्जेक्ट बनाता है; एक आर्ग्युमेंट URI प्रकार को निर्धारित करता है।

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | The string URI to be represented by the object being constructed |
| uriKind | [UriKind](../../urikind/) | Specifies the URI kind |


## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) कन्स्ट्रक्टर


निर्दिष्ट बेस और सापेक्ष URIs से एक [Uri](../) ऑब्जेक्ट बनाता है।

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The base URI |
| relativeUri | const [String](../../string/)\& | The relative URI that is added to the base URI |


## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) कन्स्ट्रक्टर


निर्दिष्ट बेस और सापेक्ष URIs से एक [Uri](../) ऑब्जेक्ट बनाता है।

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The base URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The relative URI that is added to the base URI |


## देखें

* एन्यूम [UriKind](../../urikind/)
* टाइपडेफ [SharedPtr](../../sharedptr/)
* क्लास [String](../../string/)
* क्लास [Uri](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)