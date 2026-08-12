---
title: VerifyData()
second_title: Aspose.Slides for C++ API संदर्भ
description: डेटा हस्ताक्षर की जाँच करता है।
type: docs
weight: 209
url: /hi/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) विधि

डेटा हस्ताक्षर की जाँच करता है।

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) के लिए हस्ताक्षर की जाँच। |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | उपयोग करने के लिए हैश एल्गोरिथ्म। |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | प्राप्त हस्ताक्षर। |

### रिटर्न वैल्यू

यदि हस्ताक्षर वैध है तो True, अन्यथा False।

## देखें

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [RSACryptoServiceProvider](../)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)