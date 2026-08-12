---
title: StreamWriter()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक StreamWriter ऑब्जेक्ट का उदाहरण बनाता है जो निर्दिष्ट अंतर्निहित स्ट्रीम में अक्षर लिखता है, UTF-8 एन्कोडिंग और डिफ़ॉल्ट आकार 1024 बाइट्स के बफ़र का उपयोग करता है।
type: docs
weight: 1
url: /hi/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) निर्माता


एक [StreamWriter](../) ऑब्जेक्ट का उदाहरण बनाता है जो निर्दिष्ट अंतर्निहित स्ट्रीम में अक्षर लिखता है, UTF-8 एन्कोडिंग और डिफ़ॉल्ट आकार 1024 बाइट्स के बफ़र का उपयोग करता है।

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | अक्षर लिखने के लिए अंतर्निहित स्ट्रीम |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) निर्माता


एक [StreamWriter](../) ऑब्जेक्ट का उदाहरण बनाता है जो निर्दिष्ट अंतर्निहित स्ट्रीम में अक्षर लिखता है, निर्दिष्ट एन्कोडिंग और डिफ़ॉल्ट आकार 1024 बाइट्स के बफ़र का उपयोग करता है।

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | अक्षर लिखने के लिए अंतर्निहित स्ट्रीम |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | उपयोग करने वाली एन्कोडिंग |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) निर्माता


एक [StreamWriter](../) ऑब्जेक्ट का उदाहरण बनाता है जो निर्दिष्ट अंतर्निहित स्ट्रीम में अक्षर लिखता है, निर्दिष्ट एन्कोडिंग और निर्दिष्ट आकार के बफ़र का उपयोग करता है। एक पैरामीटर यह निर्दिष्ट करता है कि क्या अंतर्निहित स्ट्रीम को [StreamWriter](../) ऑब्जेक्ट के नष्ट होने पर बंद किया जाना चाहिए।

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | अक्षर लिखने के लिए अंतर्निहित स्ट्रीम |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | उपयोग करने वाली एन्कोडिंग |
| buffer_size | int | बफ़र का न्यूनतम आकार बाइट्स में |
| leave_open | **bool** | यह निर्दिष्ट करता है कि वर्तमान [StreamWriter](../) ऑब्जेक्ट के नष्ट होने के बाद अंतर्निहित स्ट्रीम खुला छोड़ना है या नहीं |

## StreamWriter::StreamWriter(const String\&) निर्माता


एक [StreamWriter](../) ऑब्जेक्ट का उदाहरण बनाता है जो निर्दिष्ट फ़ाइल में अक्षर लिखता है, UTF-8 एन्कोडिंग और डिफ़ॉल्ट आकार 1024 बाइट्स के बफ़र का उपयोग करता है।

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | अक्षर लिखने के लिए फ़ाइल का पथ |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) निर्माता


एक [StreamWriter](../) ऑब्जेक्ट का उदाहरण बनाता है जो निर्दिष्ट फ़ाइल में अक्षर लिखता है, निर्दिष्ट एन्कोडिंग और डिफ़ॉल्ट आकार 1024 बाइट्स के बफ़र का उपयोग करता है। एक पैरामीटर यह निर्दिष्ट करता है कि डेटा फ़ाइल में जोड़ा जाना चाहिए या फ़ाइल को अधिलेखित किया जाना चाहिए।

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | अक्षर लिखने के लिए फ़ाइल का पथ |
| append | **bool** | यह निर्दिष्ट करता है कि डेटा को निर्दिष्ट फ़ाइल में जोड़ा जाना चाहिए (true) या फ़ाइल को अधिलेखित किया जाना चाहिए (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | उपयोग करने वाली एन्कोडिंग |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) निर्माता


एक [StreamWriter](../) ऑब्जेक्ट का उदाहरण बनाता है जो निर्दिष्ट फ़ाइल में अक्षर लिखता है, निर्दिष्ट एन्कोडिंग और बफ़र आकार का उपयोग करता है। एक पैरामीटर यह निर्दिष्ट करता है कि डेटा फ़ाइल में जोड़ा जाना चाहिए या फ़ाइल को अधिलेखित किया जाना चाहिए।

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | अक्षर लिखने के लिए फ़ाइल का पथ |
| append | **bool** | यह निर्दिष्ट करता है कि डेटा को निर्दिष्ट फ़ाइल में जोड़ा जाना चाहिए (true) या फ़ाइल को अधिलेखित किया जाना चाहिए (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | उपयोग करने वाली एन्कोडिंग |
| buffer_size | int | उपयोग करने के लिए बफ़र का आकार |

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)