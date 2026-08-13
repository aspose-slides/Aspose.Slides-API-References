---
title: BitVector32
second_title: Aspose.Slides for C++ API 레퍼런스
description: 간단하고 가벼운 비트 벡터를 제공하며, 32비트 저장소에 손쉬운 정수 또는 불리언 접근을 지원합니다.
type: docs
weight: 1
url: /ko/system.collections.specialized/bitvector32/
---
## BitVector32 클래스

간단하고 가벼운 비트 벡터를 제공하며, 손쉬운 정수 또는 [Boolean](../../system/boolean/) 접근을 통해 32비트 저장소에 접근할 수 있습니다.

```cpp
class BitVector32
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  [BitVector32](./bitvector32/)() | 새로운 빈 [BitVector32](./) 인스턴스를 초기화합니다. |
|  [BitVector32](./bitvector32/)(**int32_t**) | 지정된 내부 데이터를 사용하여 [BitVector32](./) 구조체의 새 인스턴스를 초기화합니다. |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | 지정된 값에 있는 정보를 사용하여 [BitVector32](./) 구조체의 새 인스턴스를 초기화합니다. |
| static **int32_t** [CreateMask](./createmask/)() | 시리즈에서 첫 번째 마스크를 생성합니다. |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | 시리즈에서 다음 마스크를 생성합니다. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | 지정된 최대값을 사용하여 시리즈에서 첫 번째 섹션을 생성합니다. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | 지정된 최대값을 사용하여 시리즈에서 다음 섹션을 생성합니다. |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | 지정된 객체가 현재 객체와 동일한지 여부를 결정합니다. |
| **int32_t** [get_Data](./get_data/)() | 이 비트 벡터에 저장된 원시 데이터를 반환합니다... |
| **int32_t** [GetHashCode](./gethashcode/)() const | 현재 객체에 대한 해시 코드를 반환합니다. |
| **bool** [idx_get](./idx_get/)(**int32_t**) | 지정된 모든 비트가 설정되었는지 여부를 나타내는 값을 가져옵니다. |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | 지정된 섹션의 값을 가져옵니다. |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | 지정된 모든 비트가 설정되었는지 여부를 나타내는 값을 설정합니다. |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | 지정된 섹션의 값을 설정합니다. |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | 값 매개변수에 의해 표현된 값을 문자열로 변환합니다. |
| [String](../../system/string/) [ToString](./tostring/)() const | 현재 객체에 의해 표현된 값을 문자열로 변환합니다. |
## 참고

* 네임스페이스 [System::Collections::Specialized](../)
* 라이브러리 [Aspose.Slides](../../)