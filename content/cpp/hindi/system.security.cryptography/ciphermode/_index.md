---
title: CipherMode
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ब्लॉक सिफर मोड।
type: docs
weight: 885
url: /hi/system.security.cryptography/ciphermode/
---
## CipherMode enum

ब्लॉक सिफर मोड।

```cpp
enum class CipherMode
```

### Values

| नाम | मान | विवरण |
| --- | --- | --- |
| CBC | 1 | Cipher block chaining जो वर्तमान ब्लॉक को पिछले ब्लॉक के साथ जोड़ता है ताकि एन्क्रिप्शन में सुधार हो। |
| ECB | 2 | Electronic codebook मोड जिसमें कोई अंतर-ब्लॉक प्रभाव नहीं होता; इससे एन्क्रिप्शन कमजोर हो जाता है। |
| OFB | 3 | Output feedback मोड जो बड़े इनपुट ब्लॉकों को छोटे टुकड़ों में संभालता है। |
| CFB | 4 | Cipher feedback मोड जो बड़े इनपुट ब्लॉकों को छोटे टुकड़ों में संभालता है। Mangling नियम OFB से अलग होते हैं। |
| CTS | 5 | Cipher text stealing मोड, जो सभी लेकिन अंतिम दो ब्लॉकों के लिए CBC जैसा व्यवहार करता है। |

## See Also

* Namespace [System::Security::Cryptography](../)
* Library [Aspose.Slides](../../)