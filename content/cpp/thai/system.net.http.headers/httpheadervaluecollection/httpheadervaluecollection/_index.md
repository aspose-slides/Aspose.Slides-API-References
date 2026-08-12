---
title: HttpHeaderValueCollection()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างอินสแตนซ์ใหม่.
type: docs
weight: 40
url: /th/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) คอนสตรัคเตอร์


สร้างอินสแตนซ์ใหม่.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | ชื่อส่วนหัว. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | คอลเลกชันของ HTTP headers. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) คอนสตรัคเตอร์


สร้างอินสแตนซ์ใหม่.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | ชื่อส่วนหัว. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | คอลเลกชันของ HTTP headers. |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | ตัวแทนที่ใช้ในการตรวจสอบรายการที่เพิ่มเข้ามา. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) คอนสตรัคเตอร์


สร้างอินสแตนซ์ใหม่.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | ชื่อส่วนหัว. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | คอลเลกชันของ HTTP headers. |
| specialValue | T | ค่า \"พิเศษ\". |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) คอนสตรัคเตอร์


สร้างอินสแตนซ์ใหม่.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | ชื่อส่วนหัว. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | คอลเลกชันของ HTTP headers. |
| specialValue | T | ค่า \"พิเศษ\". |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | ตัวแทนที่ใช้ในการตรวจสอบรายการที่เพิ่มเข้ามา. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* คลาส [String](../../../system/string/)
* คลาส [HttpHeaders](../../httpheaders/)
* คลาส [HttpHeaderValueCollection](../)
* เนมสเปซ [System::Net::Http::Headers](../../)
* ไลบรารี [Aspose.Slides](../../../)