---
title: AddRange()
second_title: Aspose.Slides for C++ API 참조
description: 현재 요청에 'Range' 헤더를 추가합니다.
type: docs
weight: 690
url: /ko/system.net/httpwebrequest/addrange/
---
## HttpWebRequest::AddRange(int32_t) 메서드

현재 요청에 '[Range](../../../system/range/)' 헤더를 추가합니다.

```cpp
virtual void System::Net::HttpWebRequest::AddRange(int32_t range)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| range | **int32_t** | 요청 범위의 시작 또는 끝. |

## HttpWebRequest::AddRange(System::String, int32_t, int32_t) 메서드

현재 요청에 '[Range](../../../system/range/)' 헤더를 추가합니다.

```cpp
virtual void System::Net::HttpWebRequest::AddRange(System::String rangeSpecifier, int32_t from, int32_t to)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rangeSpecifier | [System::String](../../../system/string/) | 범위가 지정되는 단위. |
| from | **int32_t** | 요청 범위의 시작. |
| to | **int32_t** | 요청 범위의 끝. |

## 참고

* 클래스 [HttpWebRequest](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)