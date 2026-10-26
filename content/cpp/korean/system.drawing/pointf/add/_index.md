---
title: Add()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 SizeF 객체의 너비와 높이 값을 지정된 PointF 객체의 X 및 Y 좌표 값에 각각 추가합니다.
type: docs
weight: 144
url: /ko/system.drawing/pointf/add/
---
## PointF::Add(const PointF\&, const SizeF\&) 메서드

지정된 [SizeF](../../sizef/) 객체의 너비 및 높이 값을 지정된 [PointF](../) 객체의 X 및 Y 좌표 값에 각각 추가합니다.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const SizeF &size)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | const [PointF](../)\& | 변환할 점 |
| size | const [SizeF](../../sizef/)\& | [SizeF](../../sizef/) 객체는 **point**의 좌표 값에 추가할 값을 지정합니다. |

### 반환 값

새로운 [PointF](../) 객체로, X 좌표 값은 **point**의 X 좌표 값과 **size**의 너비 값을 더한 값과 같으며, Y 좌표 값은 **point**의 Y 좌표 값과 **size**의 높이 값을 더한 값과 같습니다.

## PointF::Add(const PointF\&, const Size\&) 메서드

지정된 [Size](../../size/) 객체의 너비 및 높이 값을 지정된 [PointF](../) 객체의 X 및 Y 좌표 값에 각각 추가합니다.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const Size &size)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | const [PointF](../)\& | 변환할 점 |
| size | const [Size](../../size/)\& | [Size](../../size/) 객체는 **point**의 좌표 값에 추가할 값을 지정합니다. |

### 반환 값

새로운 [PointF](../) 객체로, X 좌표 값은 **point**의 X 좌표 값과 **size**의 너비 값을 더한 값과 같으며, Y 좌표 값은 **point**의 Y 좌표 값과 **size**의 높이 값을 더한 값과 같습니다.

## 참고

* 클래스 [PointF](../)
* 클래스 [SizeF](../../sizef/)
* 클래스 [Size](../../size/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)