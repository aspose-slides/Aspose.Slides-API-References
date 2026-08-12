---
title: UdpClient()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เริ่มต้นอินสแตนซ์ใหม่ของคลาส UdpClient.
type: docs
weight: 27
url: /th/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() คอนสตรัคเตอร์

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) คอนสตรัคเตอร์

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | ค่าที่ระบุโครงสร้างการกำหนดที่อยู่ของซ็อกเก็ต |

## UdpClient::UdpClient(int32_t) คอนสตรัคเตอร์

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| port | **int32_t** | หมายเลขพอร์ตโลคัลที่คุณต้องการสื่อสารจาก |

## UdpClient::UdpClient(int32_t, AddressFamily) คอนสตรัคเตอร์

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| port | **int32_t** | หมายเลขพอร์ตโลคัลที่คุณต้องการสื่อสารจาก |
| family | [AddressFamily](../../addressfamily/) | ค่าที่ระบุโครงสร้างการกำหนดที่อยู่ของซ็อกเก็ต |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) คอนสตรัคเตอร์

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [UdpClient](../). พารามิเตอร์ local EP จุดสิ้นสุดโลคัลที่คุณผูกการเชื่อมต่อ UDP

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของคลาส [UdpClient](../) และเชื่อมต่อไปยังโฮสต์ระยะไกลที่ระบุบนพอร์ตที่ระบุ

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | ชื่อของโฮสต์ DNS ระยะไกลที่คุณต้องการเชื่อมต่อ |
| port | **int32_t** | หมายเลขพอร์ตโลคัลที่คุณต้องการสื่อสารจาก |

## See Also

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [UdpClient](../)
* คลาส [IPEndPoint](../../../system.net/ipendpoint/)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Net::Sockets](../../)
* ไลบรารี [Aspose.Slides](../../../)