---
title: Exclude()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 영역을 지정된 사각형에서 제외한 결과로 대체합니다.
type: docs
weight: 92
url: /ko/system.drawing/region/exclude/
---
## Region::Exclude(const RectangleF\&) 메서드

현재 객체가 나타내는 영역을 지정된 사각형에서 제외한 결과로 대체합니다.

```cpp
void System::Drawing::Region::Exclude(const RectangleF &rect)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 제외할 영역을 정의하는 사각형 |

## Region::Exclude(const Rectangle\&) 메서드

현재 객체가 나타내는 영역을 지정된 사각형에서 제외한 결과로 대체합니다.

```cpp
void System::Drawing::Region::Exclude(const Rectangle &rect)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 제외할 영역을 정의하는 사각형 |

## Region::Exclude(const SharedPtr\<Drawing2D::GraphicsPath\>\&) 메서드

현재 객체가 나타내는 영역을 지정된 경로에서 제외한 결과로 대체합니다.

```cpp
void System::Drawing::Region::Exclude(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 제외할 영역을 정의하는 경로 |

## Region::Exclude(const SharedPtr\<Region\>\&) 메서드

현재 객체가 나타내는 영역을 지정된 영역에서 제외한 결과로 대체합니다.

```cpp
void System::Drawing::Region::Exclude(const SharedPtr<Region> &region)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 제외할 영역 |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [RectangleF](../../rectanglef/)
* 클래스 [Region](../)
* 클래스 [Rectangle](../../rectangle/)
* 클래스 [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)