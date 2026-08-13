---
title: ByteArrayContent()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system.net.http/bytearraycontent/bytearraycontent/
---
## ByteArrayContent::ByteArrayContent(System::ArrayPtr\<uint8_t\>) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Http::ByteArrayContent::ByteArrayContent(System::ArrayPtr<uint8_t> content)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| content | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 새 인스턴스를 초기화하는 데 사용되는 콘텐츠. |

## ByteArrayContent::ByteArrayContent(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Http::ByteArrayContent::ByteArrayContent(System::ArrayPtr<uint8_t> content, int32_t offset, int32_t count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| content | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 새 인스턴스를 초기화하는 데 사용되는 콘텐츠. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| count | **int32_t** | ‘offset’ 매개변수부터 시작하는 지정된 배열의 바이트 수. |

## 관련 항목

* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ByteArrayContent](../)
* 네임스페이스 [System::Net::Http](../../)
* 라이브러리 [Aspose.Slides](../../../)