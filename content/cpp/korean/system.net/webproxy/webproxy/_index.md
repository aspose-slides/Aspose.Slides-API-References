---
title: WebProxy()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 인스턴스를 생성합니다.
type: docs
weight: 131
url: /ko/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 프록시 서버 주소입니다. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 프록시 서버 주소입니다. |
| BypassOnLocal | **bool** | 로컬 주소에 프록시 서버를 사용해야 하는지 여부를 나타내는 값입니다. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 프록시 서버 주소입니다. |
| BypassOnLocal | **bool** | 로컬 주소에 프록시 서버를 사용해야 하는지 여부를 나타내는 값입니다. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | 프록시 서버를 사용하지 않는 주소 목록입니다. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 프록시 서버 주소입니다. |
| BypassOnLocal | **bool** | 로컬 주소에 프록시 서버를 사용해야 하는지 여부를 나타내는 값입니다. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | 프록시 서버를 사용하지 않는 주소 목록입니다. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | 인증을 위해 프록시 서버에 전송되는 자격 증명입니다. |

## WebProxy::WebProxy(String, int32_t) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| Host | [String](../../../system/string/) | 호스트 이름입니다. |
| Port | **int32_t** | 포트 번호입니다. |

## WebProxy::WebProxy(String) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::WebProxy::WebProxy(String Address)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | 프록시 서버 주소입니다. |

## WebProxy::WebProxy(String, bool) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | 프록시 서버 주소입니다. |
| BypassOnLocal | **bool** | 로컬 주소에 프록시 서버를 사용해야 하는지 여부를 나타내는 값입니다. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | 프록시 서버 주소입니다. |
| BypassOnLocal | **bool** | 로컬 주소에 프록시 서버를 사용해야 하는지 여부를 나타내는 값입니다. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | 프록시 서버를 사용하지 않는 주소 목록입니다. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | 프록시 서버 주소입니다. |
| BypassOnLocal | **bool** | 로컬 주소에 프록시 서버를 사용해야 하는지 여부를 나타내는 값입니다. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | 프록시 서버를 사용하지 않는 주소 목록입니다. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | 인증을 위해 프록시 서버에 전송되는 자격 증명입니다. |

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [WebProxy](../)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [ICredentials](../../icredentials/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)