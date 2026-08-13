---
title: GetRegionScans()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 매트릭스 변환이 적용된 후 이 Region을 근사하는 RectangleF 구조체 배열을 반환합니다.
type: docs
weight: 27
url: /ko/system.drawing/region/getregionscans/
---
## Region::GetRegionScans(const SharedPtr\<Drawing2D::Matrix\>\&) const 메서드

지정된 매트릭스 변환이 적용된 후 이 [Region](../)를 근사하는 [RectangleF](../../rectanglef/) 구조체 배열을 반환합니다.

```cpp
ArrayPtr<RectangleF> System::Drawing::Region::GetRegionScans(const SharedPtr<Drawing2D::Matrix> &matrix) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | 지역에 적용할 기하학적 변환을 나타내는 Matrix. |

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [RectangleF](../../rectanglef/)
* 클래스 [Matrix](../../../system.drawing.drawing2d/matrix/)
* 클래스 [Region](../)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)