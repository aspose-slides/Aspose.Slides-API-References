---
title: WrapSTDIOStream()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "std::basic_istream와 같은 스트림에 대한 래퍼 함수입니다."
type: docs
weight: 469
url: /ko/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) 함수

std::basic_istream와 같은 스트림에 대한 래퍼 함수입니다.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | std::basic_istream와 같은 스트림 |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | 래핑 모드 |

### 반환 값

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) 래퍼

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) 함수

std::basic_ostream와 같은 스트림에 대한 래퍼 함수입니다.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | std::basic_ostream와 같은 스트림 |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | 래핑 모드 |

### 반환 값

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) 래퍼

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) 함수

std::basic_iostream와 같은 스트림에 대한 래퍼 함수입니다.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | std::basic_iostream와 같은 스트림 |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | 래핑 모드 |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | 읽기와 쓰기 위치가 다를 경우 선호되는 위치 |

### 반환 값

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) 래퍼

## 관련 항목

* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Typedef [SharedPtr](../../system/sharedptr/)
* 클래스 [Stream](../stream/)
* 네임스페이스 [System::IO](../)
* 라이브러리 [Aspose.Slides](../../)