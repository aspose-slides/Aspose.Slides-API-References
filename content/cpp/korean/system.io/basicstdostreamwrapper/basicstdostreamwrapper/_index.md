---
title: BasicSTDOStreamWrapper()
second_title: Aspose.Slides for C++ API 레퍼런스
description: BasicSTDOStreamWrapper의 새 인스턴스를 생성합니다.
type: docs
weight: 14
url: /ko/system.io/basicstdostreamwrapper/basicstdostreamwrapper/
---
## BasicSTDOStreamWrapper::BasicSTDOStreamWrapper(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) 생성자

새 인스턴스를 생성합니다 [BasicSTDOStreamWrapper](../).

```cpp
System::IO::BasicSTDOStreamWrapper<T, typename>::BasicSTDOStreamWrapper(std::basic_ostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str | std::basic_ostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | 스트림에 대한 참조 |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | 래핑 모드 |

## BasicSTDOStreamWrapper::BasicSTDOStreamWrapper(const BasicSTDOStreamWrapper\&) 생성자

복사 생성자. 삭제됨.

```cpp
System::IO::BasicSTDOStreamWrapper<T, typename>::BasicSTDOStreamWrapper(const BasicSTDOStreamWrapper &)=delete
```

## 참고

* Enum [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* Typedef [char_type](../../stdiostreamwrapperbase/char_type/)
* Typedef [traits_type](../../stdiostreamwrapperbase/traits_type/)
* 클래스 [BasicSTDOStreamWrapper](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)