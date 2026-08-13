---
title: FieldAttributes
second_title: Aspose.Slides for C++ API 레퍼런스
description: 반영된 필드 속성.
type: docs
weight: 170
url: /ko/system.reflection/fieldattributes/
---
## FieldAttributes 열거형

반영된 필드 속성.

```cpp
enum class FieldAttributes
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| FieldAccessMask | 7 | 멤버 접근 마스크. 이 마스크를 사용하여 접근성 정보를 가져옵니다. |
| PrivateScope | 0 | 참조할 수 없는 멤버. |
| Private | 1 | 개인 멤버. |
| FamANDAssem | 2 | 개인 및 어셈블리 범위 멤버. |
| Assembly | 3 | 어셈블리 범위 멤버. |
| Family | 4 | 타입 및 하위 타입에서 접근 가능한 멤버. |
| FamORAssem | 5 | 타입, 하위 타입 및 어셈블리에서 접근 가능한 멤버. |
| Public | 6 | 모든 사람이 접근 가능한 멤버. |
| Static | 16 | 인스턴스 멤버와 반대되는 정적 멤버. |
| InitOnly | 32 | 초기화만 가능하고 변경할 수 없는 const 멤버. |
| Literal | 64 | 컴파일 시 상수 멤버. |
| NotSerialized | 128 | 직렬화되지 않은 멤버. |
| SpecialName | 512 | 아래 이름 중 하나인 특수 필드. |
| PinvokeImpl | 8192 | 인터옵 전달 구현. |
| ReservedMask | 38144 | 런타임 전용 예약 플래그. |
| RTSpecialName | 1024 | 런타임에서 이름 인코딩을 확인해야 합니다. |
| HasFieldMarshal | 4096 | 마샬링 정보가 존재합니다. |
| HasDefault | 32768 | 기본값이 존재합니다. |
| HasFieldRVA | 256 | RVA가 존재합니다. |

## 참고

* Namespace [System::Reflection](../)
* Library [Aspose.Slides](../../)