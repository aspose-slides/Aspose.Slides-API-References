---
title: StreamReader()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: StreamReader ऑब्जेक्ट का एक उदाहरण बनाता है जो निर्दिष्ट अंतर्निहित स्ट्रीम से UTF-8 एन्कोडिंग का उपयोग करके और डिफ़ॉल्ट आकार 1024 बाइट्स के बफ़र के साथ अक्षर पढ़ता है।
type: docs
weight: 1
url: /hi/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) निर्माता


निर्धारित अंतर्निहित स्ट्रीम से UTF-8 एन्कोडिंग का उपयोग करके और डिफ़ॉल्ट आकार 1024 बाइट्स के बफ़र के साथ अक्षरों को पढ़ने वाले [StreamReader](../) ऑब्जेक्ट का एक उदाहरण बनाता है।

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```


### आर्गुमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | अक्षर पढ़ने के लिए अंतर्निहित स्ट्रीम |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) निर्माता


निर्धारित अंतर्निहित स्ट्रीम से UTF-8 एन्कोडिंग का उपयोग करके और डिफ़ॉल्ट आकार 1024 बाइट्स के बफ़र के साथ अक्षरों को पढ़ने वाले [StreamReader](../) ऑब्जेक्ट का एक उदाहरण बनाता है। एक पैरामीटर यह निर्दिष्ट करता है कि बाइट ऑर्डर मार्क का पता लगाना सक्षम होना चाहिए या नहीं।

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```


### आर्गुमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | अक्षर पढ़ने के लिए अंतर्निहित स्ट्रीम |
| detectEncodingFromByteOrderMarks | **bool** | स्ट्रीम की शुरुआत में बाइट ऑर्डर मार्क खोजने के लिए सत्य, अन्यथा - असत्य |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) निर्माता


निर्धारित अंतर्निहित स्ट्रीम से निर्दिष्ट एन्कोडिंग का उपयोग करके और डिफ़ॉल्ट आकार 1024 बाइट्स के बफ़र के साथ अक्षरों को पढ़ने वाले [StreamReader](../) ऑब्जेक्ट का एक उदाहरण बनाता है।

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


### आर्गुमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | अक्षर पढ़ने के लिए अंतर्निहित स्ट्रीम |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | उपयोग करने के लिए एन्कोडिंग |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) निर्माता


निर्धारित अंतर्निहित स्ट्रीम से निर्दिष्ट एन्कोडिंग का उपयोग करके और डिफ़ॉल्ट आकार 1024 बाइट्स के बफ़र के साथ अक्षरों को पढ़ने वाले [StreamReader](../) ऑब्जेक्ट का एक उदाहरण बनाता है। एक पैरामीटर यह निर्दिष्ट करता है कि बाइट ऑर्डर मार्क का पता लगाना सक्षम होना चाहिए या नहीं।

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


### आर्गुमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | अक्षर पढ़ने के लिए अंतर्निहित स्ट्रीम |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | उपयोग करने के लिए एन्कोडिंग |
| detectEncodingFromByteOrderMarks | **bool** | स्ट्रीम की शुरुआत में बाइट ऑर्डर मार्क खोजने के लिए सत्य, अन्यथा - असत्य |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) निर्माता


निर्धारित अंतर्निहित स्ट्रीम से निर्दिष्ट एन्कोडिंग का उपयोग करके और निर्दिष्ट आकार के बफ़र के साथ अक्षरों को पढ़ने वाले [StreamReader](../) ऑब्जेक्ट का एक उदाहरण बनाता है। एक पैरामीटर यह निर्दिष्ट करता है कि बाइट ऑर्डर मार्क का पता लगाना सक्षम होना चाहिए या नहीं।

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


### आर्गुमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | अक्षर पढ़ने के लिए अंतर्निहित स्ट्रीम |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | उपयोग करने के लिए एन्कोडिंग |
| detectEncodingFromByteOrderMarks | **bool** | स्ट्रीम की शुरुआत में बाइट ऑर्डर मार्क खोजने के लिए सत्य, अन्यथा - असत्य |
| bufferSize | int | बफ़र का न्यूनतम आकार बाइट्स में |

## StreamReader::StreamReader(const System::String\&) निर्माता


निर्धारित फ़ाइल से UTF-8 एन्कोडिंग का उपयोग करके और डिफ़ॉल्ट आकार 4096 बाइट्स के बफ़र के साथ अक्षरों को पढ़ने वाले [StreamReader](../) ऑब्जेक्ट का एक उदाहरण बनाता है।

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```


### आर्गुमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | फ़ाइल का पथ जिससे अक्षर पढ़ने हैं |

## StreamReader::StreamReader(const System::String\&, bool) निर्माता


निर्धारित फ़ाइल से UTF-8 एन्कोडिंग का उपयोग करके और डिफ़ॉल्ट आकार 4096 बाइट्स के बफ़र के साथ अक्षरों को पढ़ने वाले [StreamReader](../) ऑब्जेक्ट का एक उदाहरण बनाता है। एक पैरामीटर यह निर्दिष्ट करता है कि बाइट ऑर्डर मार्क का पता लगाना सक्षम होना चाहिए या नहीं।

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```


### आर्गुमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | फ़ाइल का पथ जिससे अक्षर पढ़ने हैं |
| detectEncodingFromByteOrderMarks | **bool** | फ़ाइल की शुरुआत में बाइट ऑर्डर मार्क खोजने के लिए सत्य, अन्यथा - असत्य |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) निर्माता


निर्धारित फ़ाइल से निर्दिष्ट एन्कोडिंग का उपयोग करके और डिफ़ॉल्ट आकार 4096 बाइट्स के बफ़र के साथ अक्षरों को पढ़ने वाले [StreamReader](../) ऑब्जेक्ट का एक उदाहरण बनाता है।

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```


### आर्गुमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | फ़ाइल का पथ जिससे अक्षर पढ़ने हैं |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | उपयोग करने के लिए एन्कोडिंग |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) निर्माता


निर्धारित फ़ाइल से निर्दिष्ट एन्कोडिंग का उपयोग करके और डिफ़ॉल्ट आकार 4096 बाइट्स के बफ़र के साथ अक्षरों को पढ़ने वाले [StreamReader](../) ऑब्जेक्ट का एक उदाहरण बनाता है। एक पैरामीटर यह निर्दिष्ट करता है कि बाइट ऑर्डर मार्क का पता लगाना सक्षम होना चाहिए या नहीं।

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


### आर्गुमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | फ़ाइल का पथ जिससे अक्षर पढ़ने हैं |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | उपयोग करने के लिए एन्कोडिंग |
| detectEncodingFromByteOrderMarks | **bool** | फ़ाइल की शुरुआत में बाइट ऑर्डर मार्क खोजने के लिए सत्य, अन्यथा - असत्य |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) निर्माता


निर्धारित फ़ाइल से निर्दिष्ट एन्कोडिंग का उपयोग करके और निर्दिष्ट आकार के बफ़र के साथ अक्षरों को पढ़ने वाले [StreamReader](../) ऑब्जेक्ट का एक उदाहरण बनाता है। एक पैरामीटर यह निर्दिष्ट करता है कि बाइट ऑर्डर मार्क का पता लगाना सक्षम होना चाहिए या नहीं।

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


### आर्गुमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | फ़ाइल का पथ जिससे अक्षर पढ़ने हैं |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | उपयोग करने के लिए एन्कोडिंग |
| detectEncodingFromByteOrderMarks | **bool** | फ़ाइल की शुरुआत में बाइट ऑर्डर मार्क खोजने के लिए सत्य, अन्यथा - असत्य |
| bufferSize | int | बफ़र का न्यूनतम आकार बाइट्स में |

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)