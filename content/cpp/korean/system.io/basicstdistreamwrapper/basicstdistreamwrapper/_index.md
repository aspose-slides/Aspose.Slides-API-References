---
title: BasicSTDIStreamWrapper()
second_title: Aspose.Slides for C++ API 레퍼런스
description: BasicSTDIStreamWrapper의 새 인스턴스를 생성합니다.
type: docs
weight: 14
url: /ko/system.io/basicstdistreamwrapper/basicstdistreamwrapper/
---
## BasicSTDIStreamWrapper::BasicSTDIStreamWrapper(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) constructor


새 인스턴스를 생성합니다 [BasicSTDIStreamWrapper](../).

```cpp
System::IO::BasicSTDIStreamWrapper<T, typename>::BasicSTDIStreamWrapper(std::basic_istream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | std::basic_istream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | 스트림에 대한 참조 |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | 래핑 모드 |

## BasicSTDIStreamWrapper::BasicSTDIStreamWrapper(const BasicSTDIStreamWrapper\&) constructor


복사 생성자. 삭제되었습니다.

```cpp
System::IO::BasicSTDIStreamWrapper<T, typename>::BasicSTDIStreamWrapper(const BasicSTDIStreamWrapper &)=delete
```

## 참고

* 열거형 [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* 타입 정의 [char_type](../../stdiostreamwrapperbase/char_type/)
* 타입 정의 [traits_type](../../stdiostreamwrapperbase/traits_type/)
* 클래스 [BasicSTDIStreamWrapper](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)