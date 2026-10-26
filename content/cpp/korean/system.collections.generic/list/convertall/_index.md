---
title: ConvertAll()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 다른 유형으로 변환된 요소들의 리스트를 생성합니다.
type: docs
weight: 352
url: /ko/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) 메서드

다른 유형으로 변환된 요소들의 리스트를 생성합니다.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| OutputType | Output 리스트 요소 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | 항목 변환에 사용할 변환기. |

### 반환값

변환된 요소들의 새로 만든 리스트.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Converter](../../../system/converter/)
* 클래스 [List](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)