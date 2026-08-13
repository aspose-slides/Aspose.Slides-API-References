---
title: Subtract()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 SizeF 객체의 너비와 높이 값을 지정된 PointF 객체의 X 및 Y 좌표 값에서 각각 빼줍니다.
type: docs
weight: 157
url: /ko/system.drawing/pointf/subtract/
---
## PointF::Subtract(const PointF\&, const SizeF\&) 메서드

지정된 [SizeF](../../sizef/) 객체의 너비와 높이 값을 지정된 [PointF](../) 객체의 X 및 Y 좌표 값에서 각각 빼줍니다.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const SizeF &size)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | const [PointF](../)\& | 변환할 point |
| size | const [SizeF](../../sizef/)\& | [SizeF](../../sizef/) 객체는 **point**의 좌표 값에서 빼야 할 값을 지정합니다. |

### 반환 값

새로운 [PointF](../) 객체는 **point**의 X 좌표 값에서 **size**의 너비 값을 빼서 얻은 결과와, **point**의 Y 좌표 값에서 **size**의 높이 값을 빼서 얻은 결과를 각각 X 및 Y 좌표 값으로 갖습니다.

## PointF::Subtract(const PointF\&, const Size\&) 메서드

지정된 [Size](../../size/) 객체의 너비와 높이 값을 지정된 [PointF](../) 객체의 X 및 Y 좌표 값에서 각각 빼줍니다.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const Size &size)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | const [PointF](../)\& | 변환할 point |
| size | const [Size](../../size/)\& | [Size](../../size/) 객체는 **point**의 좌표 값에서 빼야 할 값을 지정합니다. |

### 반환 값

새로운 [PointF](../) 객체는 **point**의 X 좌표 값에서 **size**의 너비 값을 빼서 얻은 결과와, **point**의 Y 좌표 값에서 **size**의 높이 값을 빼서 얻은 결과를 각각 X 및 Y 좌표 값으로 갖습니다.

## 참고

* 클래스 [PointF](../)
* 클래스 [SizeF](../../sizef/)
* 클래스 [Size](../../size/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)