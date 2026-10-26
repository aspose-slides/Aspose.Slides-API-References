---
title: "System::TestPredicates::TypeTraits"
second_title: Aspose.Slides for C++ API 참조
description: 
type: docs
weight: 963
url: /ko/system.testpredicates.typetraits/
---
## 구조체

| 구조체 | 설명 |
| --- | --- |
| [has_data_method](./has_data_method/) | 형식에 data() 메서드가 있는지 확인합니다. 존재하면 std::true_type를 상속하고, 그렇지 않으면 std::false_type를 상속합니다. |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | BitArray 형식에 대한 특수화로, 해당 위치에서 접근할 수 없는 boost 형식을 제공합니다. |
| [has_print_to_method](./has_print_to_method/) | 주어진 형식을 첫 번째 인수로 받는 PrintTo 함수의 오버로드가 있는지 확인합니다. 오버로드가 존재하면 std::true_type를 상속하고, 그렇지 않으면 std::false_type를 상속합니다. |
| [IsCppContainer](./iscppcontainer/) | 특정 형식이 STL 스타일 컨테이너인지 확인합니다. 이를 위해 iterator 및 const_iterator 멤버 형식의 존재 여부를 확인합니다. 두 형식이 모두 존재하면 std::true_type를 상속하고, 그렇지 않으면 std::false_type를 상속합니다. |
| [IsEnumerable](./isenumerable/) | 형식이 [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/) 특수화를 기본 형식으로 가지고 있는지 확인합니다. 그렇다면 value 멤버가 true로 설정되고, 그렇지 않으면 false로 설정됩니다. |
| [LargestFPType](./largestfptype/) | 가능한 가장 긴 부동 소수점 형식에 대한 별칭을 제공하며, 부동 소수점이 아닌 형식은 무시합니다. |

## 타입 정의

| 타입 정의 | 설명 |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | **T1**이 산술형이고 **T2**가 부동 소수점 형식이거나 그 반대인지 확인합니다. 해당되면 value 멤버를 true로 설정하고, 그렇지 않으면 false로 설정합니다. |
| [AnyOfDecimal](./anyofdecimal/) | 형식 인수 중 적어도 하나가 [System::Decimal](../system/decimal/)인지 확인합니다. 해당되면 value 멤버를 true로 설정하고, 그렇지 않으면 false로 설정합니다. |
| [IsArray](./isarray/) | 형식이 [System::Array](../system/array/) 특수화인지 확인합니다. 해당되면 value 멤버를 true로 설정하고, 그렇지 않으면 false로 설정합니다. |
| [IsList](./islist/) | 형식이 [System::Collections::Generic::List](../system.collections.generic/list/) 특수화인지 확인합니다. 해당되면 value 멤버를 true로 설정하고, 그렇지 않으면 false로 설정합니다. |
| [BothArrayOrList](./botharrayorlist/) | 두 형식 인수가 모두 배열 또는 리스트인지 확인합니다. 해당되면 value 멤버를 true로 설정하고, 그렇지 않으면 false로 설정합니다. |
| [BothEnumerable](./bothenumerable/) | 두 형식 인수가 모두 IEnumerable인지 확인합니다. 해당되면 value 멤버를 true로 설정하고, 그렇지 않으면 false로 설정합니다. |