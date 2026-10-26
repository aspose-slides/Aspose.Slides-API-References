---
title: Decrypt()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट पैडिंग मोड का उपयोग करके इनपुट डेटा को डिक्रिप्ट करता है।
type: docs
weight: 27
url: /hi/system.security.cryptography/rsa/decrypt/
---
## RSA::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) विधि


Decrypts input data using the specified padding mode.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```


### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) array को डिक्रिप्ट करने के लिए। |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | पैडिंग मोड। |

### Return Value

बाइट एरे फ़ॉर्मेट में डिक्रिप्ट किया गया डेटा।

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)