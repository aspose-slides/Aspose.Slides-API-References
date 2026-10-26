---
title: LineTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 경로 끝에 선을 추가합니다
type: docs
weight: 79
url: /ko/aspose.slides/igeometrypath/lineto/
---
## IGeometryPath::LineTo(System::Drawing::PointF) 메서드

경로 끝에 선을 추가합니다

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(System::Drawing::PointF point)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | 선의 끝점 |

## IGeometryPath::LineTo(float, float) 메서드

경로 끝에 선을 추가합니다

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(float x, float y)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | **float** | 선 끝점의 X 좌표 |
| y | **float** | 선 끝점의 Y 좌표 |

## IGeometryPath::LineTo(System::Drawing::PointF, uint32_t) 메서드

경로의 지정된 위치에 선을 추가합니다

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(System::Drawing::PointF point, uint32_t index)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | 끝점 |
| index | **uint32_t** | PathData 내 세그먼트의 인덱스 |

## IGeometryPath::LineTo(float, float, uint32_t) 메서드

경로의 지정된 위치에 선을 추가합니다

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(float x, float y, uint32_t index)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | **float** | 점의 X 좌표 |
| y | **float** | 점의 Y 좌표 |
| index | **uint32_t** | PathData 내 세그먼트의 인덱스 |

## 참고

* 클래스 [PointF](../../../system.drawing/pointf/)
* 클래스 [IGeometryPath](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)