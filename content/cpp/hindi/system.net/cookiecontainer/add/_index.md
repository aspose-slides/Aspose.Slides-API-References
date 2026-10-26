---
title: Add()
second_title: Aspose.Slides for C++ API संदर्भ
description: कलेक्शन में एक कुकी जोड़ता है।
type: docs
weight: 105
url: /hi/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) मेथड

कलेक्शन में एक कुकी जोड़ता है।

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | जोड़ने के लिए कुकी। |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) मेथड

कलेक्शन में एक कुकी जोड़ता है।

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | जोड़ने के लिए कुकी। |
| throwOnError | **bool** | एक मान जो यह दर्शाता है कि त्रुटि होने पर अपवाद फेंका जाएगा या नहीं। |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) मेथड

निर्दिष्ट कलेक्शन से कुकीज़ को वर्तमान कलेक्शन में कॉपी करता है।

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | वह कलेक्शन जिससे कुकीज़ कॉपी की जाएँगी। |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) मेथड

निर्दिष्ट URI के लिए एक कुकी जोड़ता है।

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | कुकी का URI। |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | जोड़ने के लिए कुकी। |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) मेथड

निर्दिष्ट URI के लिए निर्दिष्ट कलेक्शन से कुकीज़ को वर्तमान कलेक्शन में कॉपी करता है।

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | कुकी का URI। |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | वह कुकी कलेक्शन जिससे कुकीज़ कॉपी की जाएँगी। |

## देखें भी

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [Cookie](../../cookie/)
* क्लास [CookieContainer](../)
* क्लास [CookieCollection](../../cookiecollection/)
* क्लास [Uri](../../../system/uri/)
* नेमस्पेस [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)