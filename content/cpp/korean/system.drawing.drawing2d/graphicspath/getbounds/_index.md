---
title: GetBounds()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 매트릭스로 변환될 때 현재 객체가 나타내는 경로를 둘러싼 사각형을 나타내는 RectangleF 객체를 반환합니다.
type: docs
weight: 339
url: /ko/system.drawing.drawing2d/graphicspath/getbounds/
---
## GraphicsPath::GetBounds(const MatrixPtr\&, const SharedPtr\<Pen\>\&) const 메서드

현재 객체가 지정된 매트릭스로 변환될 때 해당 경로를 둘러싼 사각형을 나타내는 [RectangleF](../../../system.drawing/rectanglef/) 객체를 반환합니다.

```cpp
RectangleF System::Drawing::Drawing2D::GraphicsPath::GetBounds(const MatrixPtr &matrix=nullptr, const SharedPtr<Pen> &pen=nullptr) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | 변환 매트릭스 |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../../system.drawing/pen/)\>\& | 경계 사각형을 계산하기 위한 [Pen](../../../system.drawing/pen/) |

## 관련 항목

* typedef [MatrixPtr](../../matrixptr/)
* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [RectangleF](../../../system.drawing/rectanglef/)
* 클래스 [Pen](../../../system.drawing/pen/)
* 클래스 [GraphicsPath](../)
* 네임스페이스 [System::Drawing::Drawing2D](../../)
* 라이브러리 [Aspose.Slides](../../../)