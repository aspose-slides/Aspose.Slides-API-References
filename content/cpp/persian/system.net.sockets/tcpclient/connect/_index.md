---
title: Connect()
second_title: مستندات API Aspose.Slides برای C++
description: اتصال به میزبان راه دور مشخص‌شده را برقرار می‌کند.
type: docs
weight: 248
url: /fa/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) متد

اتصال به میزبان راه دور مشخص‌شده را برقرار می‌کند.

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | نام میزبان راه دور برای اتصال. |
| port | **int32_t** | پورت میزبان راه دور برای اتصال. |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) متد

اتصال به میزبان راه دور مشخص‌شده را برقرار می‌کند.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | آدرس IP میزبان راه دور. |
| port | **int32_t** | پورت میزبان راه دور برای اتصال. |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) متد

اتصال به میزبان راه دور مشخص‌شده را برقرار می‌کند.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | میزبان راه دور برای اتصال. |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) متد

اتصال به میزبان راه دور مشخص‌شده را برقرار می‌کند.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | آدرس‌های IP میزبان راه دور. |
| port | **int32_t** | پورت میزبان راه دور برای اتصال. |

## مراجعه

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [String](../../../system/string/)
* کلاس [TcpClient](../)
* کلاس [IPAddress](../../../system.net/ipaddress/)
* کلاس [IPEndPoint](../../../system.net/ipendpoint/)
* فضای‌نام [System::Net::Sockets](../../)
* کتابخانه [Aspose.Slides](../../../)