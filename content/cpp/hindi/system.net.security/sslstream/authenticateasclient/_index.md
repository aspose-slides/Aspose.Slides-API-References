---
title: AuthenticateAsClient()
second_title: Aspose.Slides for C++ API संदर्भ
description: कनेक्शन के क्लाइंट-साइड को प्रमाणित करता है।
type: docs
weight: 339
url: /hi/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) विधि

कनेक्शन के क्लाइंट-साइड को प्रमाणित करता है।

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | वर्तमान उदाहरण को साझा करने वाले सर्वर का नाम। |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) विधि

कनेक्शन के क्लाइंट-साइड को प्रमाणित करता है।

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | वर्तमान उदाहरण को साझा करने वाले सर्वर का नाम। |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | क्लाइंट प्रमाणपत्र। |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | प्रमाणीकरण के लिए उपयोग किए जाने वाले SSL प्रोटोकॉल। |
| checkCertificateRevocation | **bool** | प्रमाणीकरण के दौरान प्रमाणपत्र निरस्तीकरण सूची की जाँच करनी है या नहीं, यह दर्शाने वाला मान। |

## देखें

* एन्यूम [SslProtocols](../../../system.security.authentication/sslprotocols/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [SslStream](../)
* क्लास [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* नामस्थान [System::Net::Security](../../)
* लाइब्रेरी [Aspose.Slides](../../../)