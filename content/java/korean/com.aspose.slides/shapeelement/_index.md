---
title: ShapeElement
second_title: Aspose.Slides for Java API 레퍼런스
description: 동일한 외곽선 및 채우기 속성을 가진 도형의 일부를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/shapeelement/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

동일한 외곽선 및 채우기 속성을 가진 도형의 일부를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getParentShape()](#getParentShape--) | 요소가 생성된 Shape_PPT를 반환합니다. |
| [getPathPoints()](#getPathPoints--) | 요소 경로의 기하학을 정의하는 점들의 배열을 가져옵니다. |
| [getPathTypes()](#getPathTypes--) | 요소 경로의 각 점 유형을 지정하는 바이트 값 배열을 가져옵니다. |
| [getFillSource()](#getFillSource--) | 요소를 채우는 방법에 대한 정보를 반환합니다. |
| [getStrokeSource()](#getStrokeSource--) | 요소를 스트로크하는 방법에 대한 정보를 반환합니다. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

요소가 생성된 Shape_PPT를 반환합니다. 읽기 전용 [Shape](../../com.aspose.slides/shape).

**반환:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final Point2D.Float[] getPathPoints()
```

요소 경로의 기하학을 정의하는 점들의 배열을 가져옵니다.

**반환:**
java.awt.geom.Point2D.Float[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

요소 경로의 각 점 유형을 지정하는 바이트 값 배열을 가져옵니다.

**0** 점이 도형의 시작임을 나타냅니다.

**1** 점이 선의 두 끝점 중 하나임을 나타냅니다.

**3** 점이 삼차 베지어 스플라인의 끝점 또는 제어점임을 나타냅니다.

**7** 세 개의 저차 비트를 제외한 모든 비트를 마스크합니다. 이는 점 유형을 나타냅니다.

**16** 해당 세그먼트가 점선임을 지정합니다.

**32** 점이 마커임을 지정합니다.

**128** 점이 닫힌 하위 경로(도형)의 마지막 점임을 지정합니다.

**129** 점이 선 세그먼트 끝점이면서 닫힌 하위 경로의 마지막 점임을 나타냅니다.

**반환:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

요소를 채우는 방법에 대한 정보를 반환합니다. 읽기 전용 [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**반환:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

요소를 스트로크하는 방법에 대한 정보를 반환합니다. 읽기 전용 [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**반환:**
byte