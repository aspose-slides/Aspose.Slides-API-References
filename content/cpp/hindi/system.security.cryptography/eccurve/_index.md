---
title: ECCurve
second_title: Aspose.Slides for C++ API संदर्भ
description: एक दीर्घवृत्तीय वक्र।
type: docs
weight: 716
url: /hi/system.security.cryptography/eccurve/
---
## ECCurve संरचना

एक दीर्घवृत्तीय वक्र।

```cpp
class ECCurve
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | निर्दिष्ट OID फ्रेंडली नाम से वक्र बनाएं। |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | निर्दिष्ट oid से वक्र बनाएं। |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | निर्दिष्ट OID मान से वक्र बनाएं। |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | नामित वक्र को दर्शाने वाला [Oid](../oid/) प्राप्त करता है। |
| void [Validate](./validate/)() const | वर्तमान वक्र को मान्य करें। |

## एनम

| एनम | विवरण |
| --- | --- |
| [ECCurveType](./eccurvetype/) | दीर्घवृत्तीय वक्र का प्रकार। |

## संबंधित देखें

* नामस्थान [System::Security::Cryptography](../)
* पुस्तकालय [Aspose.Slides](../../)