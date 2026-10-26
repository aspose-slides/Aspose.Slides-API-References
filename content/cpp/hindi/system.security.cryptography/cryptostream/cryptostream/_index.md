---
title: CryptoStream()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: कंस्ट्रक्टर।
type: docs
weight: 1
url: /hi/system.security.cryptography/cryptostream/cryptostream/
---
## CryptoStream::CryptoStream(const SharedPtr\<System::IO::Stream\>\&, const SharedPtr\<ICryptoTransform\>\&, CryptoStreamMode) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::Security::Cryptography::CryptoStream::CryptoStream(const SharedPtr<System::IO::Stream> &stream, const SharedPtr<ICryptoTransform> &transform, CryptoStreamMode mode)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | रैप करने के लिए स्ट्रीम। |
| transform | const [SharedPtr](../../../system/sharedptr/)\<[ICryptoTransform](../../icryptotransform/)\>\& | डेटा को प्रोसेस करने के लिए ट्रांसफ़ॉर्मेशन फ़ंक्शन, जब इसे स्ट्रीम में भेजा/पढ़ा जाता है। |
| mode | [CryptoStreamMode](../../cryptostreammode/) | स्ट्रीम की दिशा। |

## संबंधित देखें

* Enum [CryptoStreamMode](../../cryptostreammode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [CryptoStream](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)