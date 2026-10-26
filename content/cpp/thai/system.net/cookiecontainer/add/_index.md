---
title: Add()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เพิ่มคุกกี้เข้าไปในคอลเลกชัน.
type: docs
weight: 105
url: /th/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) method

เพิ่มคุกกี้เข้าไปในคอลเลกชัน

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | คุกกี้ที่ต้องการเพิ่ม |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) method

เพิ่มคุกกี้เข้าไปในคอลเลกชัน

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | คุกกี้ที่ต้องการเพิ่ม |
| throwOnError | **bool** | ค่าที่ระบุว่าจะแสดงข้อยกเว้นเมื่อเกิดข้อผิดพลาดหรือไม่ |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) method

คัดลอกคุกกี้จากคอลเลกชันที่ระบุไปยังคอลเลกชันปัจจุบัน

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | คอลเลกชันที่คุกกี้จะถูกคัดลอกจาก |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) method

เพิ่มคุกกี้สำหรับ URI ที่ระบุ

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI ของคุกกี้ |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | คุกกี้ที่ต้องการเพิ่ม |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) method

คัดลอกคุกกี้จากคอลเลกชันที่ระบุสำหรับ URI ที่ระบุไปยังคอลเลกชันปัจจุบัน

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI ของคุกกี้ |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | คอลเลกชันคุกกี้ที่ต้องการคัดลอก |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [CookieContainer](../)
* Class [CookieCollection](../../cookiecollection/)
* Class [Uri](../../../system/uri/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)