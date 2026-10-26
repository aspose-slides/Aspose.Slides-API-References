---
title: Connect()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างการเชื่อมต่อไปยังพอร์ตที่ระบุบนโฮสต์ที่ระบุ
type: docs
weight: 66
url: /th/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) เมธอด

สร้างการเชื่อมต่อไปยังพอร์ตที่ระบุบนโฮสต์ที่ระบุ

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | ชื่อของโฮสต์ DNS ระยะไกลที่คุณต้องการเชื่อมต่อ |
| port | **int32_t** | หมายเลขพอร์ตท้องถิ่นที่คุณต้องการสื่อสาร |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) เมธอด

สร้างการเชื่อมต่อกับโฮสต์ที่อยู่ตามที่ระบุบนพอร์ตที่ระบุ

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | [IPAddress](../../../system.net/ipaddress/) ของโฮสต์ระยะไกลที่ต้องการส่งข้อมูล |
| port | **int32_t** | หมายเลขพอร์ตท้องถิ่นที่คุณต้องการสื่อสาร |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) เมธอด

สร้างการเชื่อมต่อไปยังจุดสิ้นสุดระยะไกล

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | จุดสิ้นสุดที่คุณผูกการเชื่อมต่อ UDP |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [UdpClient](../)
* คลาส [IPAddress](../../../system.net/ipaddress/)
* คลาส [IPEndPoint](../../../system.net/ipendpoint/)
* เนมสเปซ [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)