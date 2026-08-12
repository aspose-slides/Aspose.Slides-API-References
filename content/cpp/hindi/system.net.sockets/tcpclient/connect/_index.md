---
title: Connect()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट दूरस्थ होस्ट से कनेक्शन स्थापित करता है।
type: docs
weight: 248
url: /hi/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) विधि

निर्दिष्ट दूरस्थ होस्ट से कनेक्शन स्थापित करता है।

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | कनेक्ट करने के लिए दूरस्थ होस्ट का नाम। |
| port | **int32_t** | कनेक्ट करने के लिए दूरस्थ होस्ट का पोर्ट। |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) विधि

निर्दिष्ट दूरस्थ होस्ट से कनेक्शन स्थापित करता है।

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | एक दूरस्थ होस्ट का IP पता। |
| port | **int32_t** | कनेक्ट करने के लिए दूरस्थ होस्ट का पोर्ट। |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) विधि

निर्दिष्ट दूरस्थ होस्ट से कनेक्शन स्थापित करता है।

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | कनेक्ट करने के लिए एक दूरस्थ होस्ट। |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) विधि

निर्दिष्ट दूरस्थ होस्ट से कनेक्शन स्थापित करता है।

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | एक दूरस्थ होस्ट के IP पते। |
| port | **int32_t** | कनेक्ट करने के लिए दूरस्थ होस्ट का पोर्ट। |

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [String](../../../system/string/)
* क्लास [TcpClient](../)
* क्लास [IPAddress](../../../system.net/ipaddress/)
* क्लास [IPEndPoint](../../../system.net/ipendpoint/)
* नेमस्पेस [System::Net::Sockets](../../)
* लाइब्रेरी [Aspose.Slides](../../../)