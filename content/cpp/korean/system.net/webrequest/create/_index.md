---
title: Create()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 지정된 URI를 사용하여 WebRequest 클래스의 새 인스턴스를 생성합니다.
type: docs
weight: 53
url: /ko/system.net/webrequest/create/
---
## WebRequest::Create(String) 메서드


지정된 URI를 사용하여 [WebRequest](../) 클래스의 새 인스턴스를 생성합니다.

```cpp
static System::SharedPtr<WebRequest> System::Net::WebRequest::Create(String requestUriString)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | 지정된 URI를 사용하여 [WebRequest](../) 클래스의 새 인스턴스를 만드는 데 사용되는 URI입니다. |

### 반환 값

새로 생성된 WebRequest-클래스 인스턴스.

## WebRequest::Create(System::SharedPtr\<Uri\>) 메서드


지정된 URI를 사용하여 [WebRequest](../) 클래스의 새 인스턴스를 생성합니다.

```cpp
static System::SharedPtr<WebRequest> System::Net::WebRequest::Create(System::SharedPtr<Uri> requestUri)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 지정된 URI를 사용하여 [WebRequest](../) 클래스의 새 인스턴스를 만드는 데 사용되는 URI입니다. |

### 반환 값

새로 생성된 WebRequest-클래스 인스턴스.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [WebRequest](../)
* 클래스 [String](../../../system/string/)
* 클래스 [Uri](../../../system/uri/)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)