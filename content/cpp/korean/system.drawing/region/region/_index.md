---
title: Region()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Region 클래스의 새 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system.drawing/region/region/
---
## Region::Region() 생성자

새로운 [Region](../) 클래스 인스턴스를 생성합니다.

```cpp
System::Drawing::Region::Region()
```

## Region::Region(const RectangleF\&) 생성자

지정된 사각형으로 정의된 영역을 나타내는 새로운 [Region](../) 클래스 인스턴스를 생성합니다.

```cpp
System::Drawing::Region::Region(const RectangleF &rect)
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 영역을 정의하는 사각형 |

## Region::Region(const Rectangle\&) 생성자

지정된 사각형으로 정의된 영역을 나타내는 새로운 [Region](../) 클래스 인스턴스를 생성합니다.

```cpp
System::Drawing::Region::Region(const Rectangle &rect)
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 영역을 정의하는 사각형 |

## Region::Region(const SharedPtr\<Drawing2D::GraphicsPath\>\&) 생성자

지정된 경로로 정의된 영역을 나타내는 새로운 [Region](../) 클래스 인스턴스를 생성합니다.

```cpp
System::Drawing::Region::Region(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 영역을 정의하는 경로 |

## Region::Region(const SkPath\&) 생성자

```cpp
System::Drawing::Region::Region(const SkPath &path)
```

## Region::Region(const SharedPtr\<Drawing2D::RegionData\>\&) 생성자

지정된 RegionData 객체로 정의된 영역을 나타내는 새로운 [Region](../) 클래스 인스턴스를 생성합니다.

```cpp
System::Drawing::Region::Region(const SharedPtr<Drawing2D::RegionData> &region_data)
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| region_data | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::RegionData](../../../system.drawing.drawing2d/regiondata/)\>\& | 영역을 정의하는 RegionData 객체 |

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Region](../)
* 클래스 [RectangleF](../../rectanglef/)
* 클래스 [Rectangle](../../rectangle/)
* 클래스 [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 클래스 [RegionData](../../../system.drawing.drawing2d/regiondata/)
* 네임스페이스 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)