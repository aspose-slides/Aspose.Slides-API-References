---
title: BinaryReader()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्ट्रीम से डेटा पढ़ने के लिए UTF-8 एन्कोडिंग का उपयोग करने वाले BinaryReader क्लास का एक उदाहरण बनाता है।
type: docs
weight: 1
url: /hi/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) constructor

UTF-8 एन्कोडिंग वाली निर्दिष्ट स्ट्रीम से डेटा पढ़ने वाले [BinaryReader](../) क्लास का एक उदाहरण बनाता है।

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | इनपुट स्ट्रीम |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructor

निर्दिष्ट स्ट्रीम से डेटा पढ़ने के लिए निर्दिष्ट एन्कोडिंग का उपयोग करने वाला [BinaryReader](../) क्लास का एक उदाहरण बनाता है।

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | इनपुट स्ट्रीम |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | उपयोग करने के लिए एन्कोडिंग |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) constructor

निर्दिष्ट स्ट्रीम से डेटा पढ़ने के लिए निर्दिष्ट एन्कोडिंग का उपयोग करने वाला [BinaryReader](../) क्लास का एक उदाहरण बनाता है।

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | इनपुट स्ट्रीम |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | उपयोग करने के लिए एन्कोडिंग |
| leaveOpen | **bool** | यह निर्दिष्ट करता है कि वर्तमान ऑब्जेक्ट को नष्ट करने के बाद **input** स्ट्रीम को खुला (true) रखना है या नहीं (false) |

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [BinaryReader](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)