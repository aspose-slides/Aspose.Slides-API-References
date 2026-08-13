---
title: BasicSTDIOStreamWrapper()
second_title: Aspose.Slides for C++ API 참조
description: BasicSTDIOStreamWrapper의 새 인스턴스를 생성합니다.
type: docs
weight: 14
url: /ko/system.io/basicstdiostreamwrapper/basicstdiostreamwrapper/
---
## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) 생성자

[BasicSTDIOStreamWrapper](../)의 새 인스턴스를 생성합니다.

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(std::basic_iostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | std::basic_iostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | 스트림에 대한 참조 |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | 래핑 모드 |
| pref_pos | [STDIOStreamPositionPreference](../../stdiostreampositionpreference/) | 읽기 및 쓰기 위치가 다를 경우 선호되는 위치 |

## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper\&) 생성자

복사 생성자. 삭제됨.

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper &)=delete
```

## 관련 항목

* Enum [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../../stdiostreampositionpreference/)
* Typedef [char_type](../../stdiostreamwrapperbase/char_type/)
* Typedef [traits_type](../../stdiostreamwrapperbase/traits_type/)
* Class [BasicSTDIOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)