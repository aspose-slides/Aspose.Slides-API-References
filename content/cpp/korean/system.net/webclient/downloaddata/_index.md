---
title: DownloadData()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 리소스를 바이트 배열로 다운로드합니다.
type: docs
weight: 79
url: /ko/system.net/webclient/downloaddata/
---
## WebClient::DownloadData(const String\&) const method

지정된 리소스를 바이트 배열로 다운로드합니다.

```cpp
ByteArrayPtr System::Net::WebClient::DownloadData(const String &address) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| address | const [String](../../../system/string/)\& | 리소스의 URI. |

### 반환값

요청된 리소스를 포함하는 바이트 배열.

## WebClient::DownloadData(const SharedPtr\<Uri\>\&) const method

지정된 리소스를 바이트 배열로 다운로드합니다.

```cpp
ByteArrayPtr System::Net::WebClient::DownloadData(const SharedPtr<Uri> &address) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| address | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | 리소스의 URI. |

### 반환값

요청된 리소스를 포함하는 바이트 배열.

## 참조

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [WebClient](../)
* 클래스 [Uri](../../../system/uri/)
* 네임스페이스 [System::Net](../../)
* Library [Aspose.Slides](../../../)