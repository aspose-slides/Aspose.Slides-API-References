---
title: WebProxy()
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: एक नया उदाहरण बनाता है।
type: docs
weight: 131
url: /hi/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() कंस्ट्रक्टर

एक नया उदाहरण बनाता है।

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) कंस्ट्रक्टर

एक नया उदाहरण बनाता है।

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | प्रॉक्सी सर्वर का पता। |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) कंस्ट्रक्टर

एक नया उदाहरण बनाता है।

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | प्रॉक्सी सर्वर का पता। |
| BypassOnLocal | **bool** | एक मान जो दर्शाता है कि स्थानीय पतों के लिए प्रॉक्सी सर्वर का उपयोग करना चाहिए या नहीं। |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) कंस्ट्रक्टर

एक नया उदाहरण बनाता है।

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | प्रॉक्सी सर्वर का पता। |
| BypassOnLocal | **bool** | एक मान जो दर्शाता है कि स्थानीय पतों के लिए प्रॉक्सी सर्वर का उपयोग करना चाहिए या नहीं। |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | ऐसे पतों की सूची जो प्रॉक्सी सर्वर का उपयोग नहीं करते। |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) कंस्ट्रक्टर

एक नया उदाहरण बनाता है।

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | प्रॉक्सी सर्वर का पता। |
| BypassOnLocal | **bool** | एक मान जो दर्शाता है कि स्थानीय पतों के लिए प्रॉक्सी सर्वर का उपयोग करना चाहिए या नहीं। |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | ऐसे पतों की सूची जो प्रॉक्सी सर्वर का उपयोग नहीं करते। |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | प्रॉक्सी सर्वर को प्रमाणित करने के लिए भेजे जाने वाले क्रेडेंशियल्स। |

## WebProxy::WebProxy(String, int32_t) कंस्ट्रक्टर

एक नया उदाहरण बनाता है।

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| Host | [String](../../../system/string/) | होस्ट नाम। |
| Port | **int32_t** | पोर्ट नंबर। |

## WebProxy::WebProxy(String) कंस्ट्रक्टर

एक नया उदाहरण बनाता है।

```cpp
System::Net::WebProxy::WebProxy(String Address)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| Address | [String](../../../system/string/) | प्रॉक्सी सर्वर का पता। |

## WebProxy::WebProxy(String, bool) कंस्ट्रक्टर

एक नया उदाहरण बनाता है।

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| Address | [String](../../../system/string/) | प्रॉक्सी सर्वर का पता। |
| BypassOnLocal | **bool** | एक मान जो दर्शाता है कि स्थानीय पतों के लिए प्रॉक्सी सर्वर का उपयोग करना चाहिए या नहीं। |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) कंस्ट्रक्टर

एक नया उदाहरण बनाता है।

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| Address | [String](../../../system/string/) | प्रॉक्सी सर्वर का पता। |
| BypassOnLocal | **bool** | एक मान जो दर्शाता है कि स्थानीय पतों के लिए प्रॉक्सी सर्वर का उपयोग करना चाहिए या नहीं। |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | ऐसे पतों की सूची जो प्रॉक्सी सर्वर का उपयोग नहीं करते। |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) कंस्ट्रक्टर

एक नया उदाहरण बनाता है।

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| Address | [String](../../../system/string/) | प्रॉक्सी सर्वर का पता। |
| BypassOnLocal | **bool** | एक मान जो दर्शाता है कि स्थानीय पतों के लिए प्रॉक्सी सर्वर का उपयोग करना चाहिए या नहीं। |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | ऐसे पतों की सूची जो प्रॉक्सी सर्वर का उपयोग नहीं करते। |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | प्रॉक्सी सर्वर को प्रमाणित करने के लिए भेजे जाने वाले क्रेडेंशियल्स। |

## संदर्भ

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [WebProxy](../)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [ICredentials](../../icredentials/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)