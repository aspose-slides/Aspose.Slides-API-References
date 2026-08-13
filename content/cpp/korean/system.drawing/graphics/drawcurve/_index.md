---
title: DrawCurve()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 펜을 사용하여 스플라인을 그립니다.
type: docs
weight: 794
url: /ko/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) 메서드

스플라인을 지정된 펜으로 그립니다.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 스플라인을 그릴 때 사용할 펜 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) 포인트는 스플라인을 결정합니다 |
| tension | **float** | 스플라인의 장력을 지정하는 값 |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) 메서드

스플라인을 지정된 펜으로 그립니다.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 스플라인을 그릴 때 사용할 펜 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) 포인트는 스플라인을 결정합니다 |
| tension | **float** | 스플라인의 장력을 지정하는 값 |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) 메서드

스플라인을 지정된 펜으로 그립니다.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 스플라인을 그릴 때 사용할 펜 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) 포인트는 스플라인을 결정합니다 |
| offset | **int32_t** | **points** 배열의 첫 번째 요소로부터 오프셋 |
| numberOfSegments | **int32_t** | 곡선에 포함시킬 세그먼트 수 |
| tension | **float** | 스플라인의 장력을 지정하는 값 |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) 메서드

스플라인을 지정된 펜으로 그립니다.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 스플라인을 그릴 때 사용할 펜 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) 포인트는 스플라인을 결정합니다 |
| offset | **int32_t** | **points** 배열의 첫 번째 요소로부터 오프셋 |
| numberOfSegments | **int32_t** | 곡선에 포함시킬 세그먼트 수 |
| tension | **float** | 스플라인의 장력을 지정하는 값 |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [Pen](../../pen/)
* 클래스 [Point](../../point/)
* 클래스 [Graphics](../)
* 클래스 [PointF](../../pointf/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)