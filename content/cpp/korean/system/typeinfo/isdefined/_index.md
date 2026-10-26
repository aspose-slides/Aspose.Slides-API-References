---
title: IsDefined()
second_title: Aspose.Slides for C++ API 참조
description: 구현되지 않음. 지정된 유형 또는 해당 파생 유형의 하나 이상의 특성이 이 멤버에 적용되었는지 여부를 나타냅니다.
type: docs
weight: 157
url: /ko/system/typeinfo/isdefined/
---
## TypeInfo::IsDefined(const TypeInfo\&, bool) const 메서드

구현되지 않음. 지정된 유형 또는 해당 파생 유형의 하나 이상의 특성이 이 멤버에 적용되었는지 여부를 나타냅니다.

```cpp
bool System::TypeInfo::IsDefined(const TypeInfo &attributeType, bool inherit) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | 검색할 사용자 정의 특성의 유형입니다. 검색에는 파생 유형이 포함됩니다. |
| inherit | **bool** | 특성 검색을 위해 이 멤버의 상속 체인을 검색하려면 true; 그렇지 않으면 false. 이 매개변수는 속성과 이벤트에 대해 무시됩니다. |

### 반환값

하나 이상의 attributeType 인스턴스 또는 해당 파생 유형이 이 멤버에 적용되면 true; 그렇지 않으면 false.

## 참조

* 클래스 [TypeInfo](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)