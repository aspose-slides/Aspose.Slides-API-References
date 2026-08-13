---
title: Details_ExceptionWithFilename
second_title: Aspose.Slides for C++ API 참조
description: 파일 이름을 포함하는 예외에 대한 템플릿 클래스입니다.
type: docs
weight: 443
url: /ko/system/details_exceptionwithfilename/
---
## Details_ExceptionWithFilename 클래스

파일 이름을 포함하는 예외에 대한 템플릿 클래스입니다.

```cpp
template<typename T,typename>class Details_ExceptionWithFilename : public T
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 예외 기본 클래스. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual [String](../string/) [get_FileName](./get_filename/)() const | 이 예외를 발생시키는 파일의 이름을 반환합니다. |
| [String](../string/) [get_Message](./get_message/)() const override |  |
| [String](../string/) [ToString](./tostring/)() const override |  |

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)