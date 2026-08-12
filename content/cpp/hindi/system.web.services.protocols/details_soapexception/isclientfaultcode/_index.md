---
title: IsClientFaultCode()
second_title: Aspose.Slides for C++ API संदर्भ
description: जाँचता है कि निर्दिष्ट कोड 'Client' SOAP फ़ॉल्ट कोड के बराबर है या नहीं।
type: docs
weight: 105
url: /hi/system.web.services.protocols/details_soapexception/isclientfaultcode/
---
## Details_SoapException::IsClientFaultCode(System::SharedPtr\<Xml::XmlQualifiedName\>) मेथड

जाँचता है कि निर्दिष्ट कोड 'Client' SOAP फ़ाल्ट कोड के बराबर है या नहीं।

```cpp
static bool System::Web::Services::Protocols::Details_SoapException::IsClientFaultCode(System::SharedPtr<Xml::XmlQualifiedName> code)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | जाँचने के लिए SOAP फ़ाल्ट कोड। |

### रिटर्न वैल्यू

True when the specified code is equal to the 'Client' SOAP fault code, otherwise false.

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* क्लास [Details_SoapException](../)
* नेमस्पेस [System::Web::Services::Protocols](../../)
* लाइब्रेरी [Aspose.Slides](../../../)