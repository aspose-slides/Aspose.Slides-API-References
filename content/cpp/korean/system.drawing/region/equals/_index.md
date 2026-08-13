---
title: Equals()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 그리기 표면에서 현재 객체가 나타내는 영역과 지정된 영역이 동일한지 여부를 결정합니다.
type: docs
weight: 157
url: /ko/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) 메서드

지정된 영역이 지정된 그리기 표면에서 현재 객체가 나타내는 영역과 동일한지 여부를 결정합니다.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 이 영역과 비교할 영역 |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 그리기 표면 |

### 반환 값

지정된 영역의 내부가 **g** 매개변수와 연관된 변환이 적용된 현재 객체가 나타내는 영역의 내부와 동일하면 True; 그렇지 않으면 false

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Region](../)
* 클래스 [Graphics](../../graphics/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)