---
title: WebProxy()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอินสแตนซ์ใหม่.
type: docs
weight: 131
url: /th/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() คอนสตรัคเตอร์


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) คอนสตรัคเตอร์


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | ที่อยู่ของเซิร์ฟเวอร์พร็อกซี. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) คอนสตรัคเตอร์


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | ที่อยู่ของเซิร์ฟเวอร์พร็อกซี. |
| BypassOnLocal | **bool** | ค่าที่ระบุว่าต้องใช้เซิร์ฟเวอร์พร็อกซีสำหรับที่อยู่ในเครื่องหรือไม่. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) คอนสตรัคเตอร์


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | ที่อยู่ของเซิร์ฟเวอร์พร็อกซี. |
| BypassOnLocal | **bool** | ค่าที่ระบุว่าต้องใช้เซิร์ฟเวอร์พร็อกซีสำหรับที่อยู่ในเครื่องหรือไม่. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | รายการที่อยู่ที่ไม่ใช้เซิร์ฟเวอร์พร็อกซี. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) คอนสตรัคเตอร์


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | ที่อยู่ของเซิร์ฟเวอร์พร็อกซี. |
| BypassOnLocal | **bool** | ค่าที่ระบุว่าต้องใช้เซิร์ฟเวอร์พร็อกซีสำหรับที่อยู่ในเครื่องหรือไม่. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | รายการที่อยู่ที่ไม่ใช้เซิร์ฟเวอร์พร็อกซี. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | ข้อมูลประจำตัวที่ส่งไปยังเซิร์ฟเวอร์พร็อกซีเพื่อการตรวจสอบสิทธิ์. |

## WebProxy::WebProxy(String, int32_t) คอนสตรัคเตอร์


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| Host | [String](../../../system/string/) | ชื่อโฮสต์. |
| Port | **int32_t** | หมายเลขพอร์ต. |

## WebProxy::WebProxy(String) คอนสตรัคเตอร์


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(String Address)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | ที่อยู่ของเซิร์ฟเวอร์พร็อกซี. |

## WebProxy::WebProxy(String, bool) คอนสตรัคเตอร์


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | ที่อยู่ของเซิร์ฟเวอร์พร็อกซี. |
| BypassOnLocal | **bool** | ค่าที่ระบุว่าต้องใช้เซิร์ฟเวอร์พร็อกซีสำหรับที่อยู่ในเครื่องหรือไม่. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) คอนสตรัคเตอร์


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | ที่อยู่ของเซิร์ฟเวอร์พร็อกซี. |
| BypassOnLocal | **bool** | ค่าที่ระบุว่าต้องใช้เซิร์ฟเวอร์พร็อกซีสำหรับที่อยู่ในเครื่องหรือไม่. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | รายการที่อยู่ที่ไม่ใช้เซิร์ฟเวอร์พร็อกซี. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) คอนสตรัคเตอร์


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | ที่อยู่ของเซิร์ฟเวอร์พร็อกซี. |
| BypassOnLocal | **bool** | ค่าที่ระบุว่าต้องใช้เซิร์ฟเวอร์พร็อกซีสำหรับที่อยู่ในเครื่องหรือไม่. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | รายการที่อยู่ที่ไม่ใช้เซิร์ฟเวอร์พร็อกซี. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | ข้อมูลประจำตัวที่ส่งไปยังเซิร์ฟเวอร์พร็อกซีเพื่อการตรวจสอบสิทธิ์. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [WebProxy](../)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [ICredentials](../../icredentials/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)