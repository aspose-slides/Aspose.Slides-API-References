---
title: StringFormat()
second_title: Aspose.Slides for C++ API 레퍼런스
description: StringFormat 클래스의 새 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() 생성자

[StringFormat](../) 클래스의 새 인스턴스를 생성합니다.

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) 생성자

[StringFormat](../) 클래스의 새 인스턴스를 지정된 형식 플래그와 언어로 생성합니다.

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | 생성되는 객체가 나타낼 문자열 형식을 지정하는 StringFormatFlags 열거형 값의 비트wise 조합 |
| language | **int32_t** | 텍스트의 언어 |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) 생성자

복사 생성자.

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | 복사할 [StringFormat](../) 객체 |

## 관련 항목

* 열거형 [StringFormatFlags](../../stringformatflags/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [StringFormat](../)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)