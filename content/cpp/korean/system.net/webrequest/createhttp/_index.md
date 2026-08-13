---
title: CreateHttp()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 URI를 사용하여 WebRequest 클래스의 새 인스턴스를 생성합니다.
type: docs
weight: 79
url: /ko/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) 메서드


지정된 URI를 사용하여 [WebRequest](../) 클래스의 새 인스턴스를 생성합니다.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | [WebRequest](../) 클래스의 새 인스턴스를 만드는 데 사용되는 URI입니다. |

### 반환 값

새로 생성된 WebRequest 클래스 인스턴스.
## 비고



지정된 URI가 [http://](http://) 또는 [https://](https://)를 제외한 다른 스키마로 시작하면 NotSupportedException이 발생합니다.

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) 메서드


지정된 URI를 사용하여 [WebRequest](../) 클래스의 새 인스턴스를 생성합니다.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | [WebRequest](../) 클래스의 새 인스턴스를 만드는 데 사용되는 URI입니다. |

### 반환 값

새로 생성된 WebRequest 클래스 인스턴스.
## 비고



지정된 URI가 [http://](http://) 또는 [https://](https://)를 제외한 다른 스키마로 시작하면 NotSupportedException이 발생합니다.

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [HttpWebRequest](../../httpwebrequest/)
* 클래스 [String](../../../system/string/)
* 클래스 [WebRequest](../)
* 클래스 [Uri](../../../system/uri/)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)