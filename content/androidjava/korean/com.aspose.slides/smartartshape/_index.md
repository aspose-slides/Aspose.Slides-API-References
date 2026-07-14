---
title: SmartArtShape
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: SmartArt 모양을 나타냅니다
type: docs
url: /ko/com.aspose.slides/smartartshape/
---
**상속:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**구현된 모든 인터페이스:**
[com.aspose.slides.ISmartArtShape](../../com.aspose.slides/ismartartshape)
```
public class SmartArtShape extends GeometryShape implements ISmartArtShape
```

SmartArt 모양을 나타냅니다
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getShapeType()](#getShapeType--) | 지오메트리 사전 설정 유형을 반환하거나 설정합니다. |
| [setShapeType(int value)](#setShapeType-int-) | 지오메트리 사전 설정 유형을 반환하거나 설정합니다. |
| [getTextFrame()](#getTextFrame--) | SmartArt 모양의 텍스트를 반환합니다. |
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

지오메트리 사전 설정 유형을 반환하거나 설정합니다. 참고: 값이 변경되면 모든 조정 값이 기본값으로 재설정됩니다. 읽기/쓰기 [ShapeType](../../com.aspose.slides/shapetype).

**반환값:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

지오메트리 사전 설정 유형을 반환하거나 설정합니다. 참고: 값이 변경되면 모든 조정 값이 기본값으로 재설정됩니다. 읽기/쓰기 [ShapeType](../../com.aspose.slides/shapetype).

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | int |  |
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

SmartArt 모양의 텍스트를 반환합니다. 읽기 전용 [ITextFrame](../../com.aspose.slides/itextframe).

**반환값:**
[ITextFrame](../../com.aspose.slides/itextframe)