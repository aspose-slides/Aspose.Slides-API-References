---
title: ShapeElement
second_title: Java API 레퍼런스를 이용한 Android용 Aspose.Slides
description: 동일한 외곽선 및 채우기 속성을 가진 도형의 일부를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/shapeelement/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

동일한 외곽선 및 채우기 속성을 가진 형태의 일부를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getParentShape()](#getParentShape--) | 요소가 생성된 Shape_PPT를 반환합니다. |
| [getPathPoints()](#getPathPoints--) | 요소 경로의 기하학을 정의하는 포인트 배열을 가져옵니다. |
| [getPathTypes()](#getPathTypes--) | 요소 경로의 각 포인트 유형을 지정하는 바이트 값 배열을 가져옵니다. |
| [getFillSource()](#getFillSource--) | 요소를 채우는 방법에 대한 정보를 반환합니다. |
| [getStrokeSource()](#getStrokeSource--) | 요소를 스트로크하는 방법에 대한 정보를 반환합니다. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```


요소가 생성된 Shape_PPT를 반환합니다. 읽기 전용 [Shape](../../com.aspose.slides/shape).

**반환값:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```


요소 경로의 기하학을 정의하는 포인트 배열을 가져옵니다.

**반환값:**
android.graphics.PointF[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```


요소 경로의 각 포인트 유형을 지정하는 바이트 값 배열을 가져옵니다.

**0** 포인트가 도형의 시작임을 나타냅니다.

**1** 포인트가 선의 두 끝점 중 하나임을 나타냅니다.

**3** 포인트가 3차 베지어 스플라인의 끝점 또는 제어점임을 나타냅니다.

**7** 포인트 유형을 나타내는 세 개의 하위 비트를 제외한 모든 비트를 마스크합니다.

**16** 해당 구간이 점선임을 지정합니다.

**32** 포인트가 마커임을 지정합니다.

**128** 포인트가 닫힌 하위 경로(도형)의 마지막 포인트임을 지정합니다.

**129** 선 구간 끝점이면서 닫힌 하위 경로의 마지막 포인트인 데이터 포인트를 나타냅니다.

**반환값:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```


요소를 채우는 방법에 대한 정보를 반환합니다. 읽기 전용 [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**반환값:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```


요소를 스트로크하는 방법에 대한 정보를 반환합니다. 읽기 전용 [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**반환값:**
byte