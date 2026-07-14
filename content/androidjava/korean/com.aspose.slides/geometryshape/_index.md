---
title: GeometryShape
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 모든 기하학적 도형의 기본 클래스를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/geometryshape/
---
**상속:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)  
```
public abstract class GeometryShape extends Shape implements IGeometryShape
```

모든 기하학적 도형의 기본 클래스입니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | 도형의 기하학적 경로 복사본을 반환합니다. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | [IGeometryPath](../../com.aspose.slides/igeometrypath) 객체에서 도형의 기하학을 업데이트합니다. |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | [IGeometryPath](../../com.aspose.slides/igeometrypath) 배열에서 도형의 기하학을 업데이트합니다. |
| [getShapeStyle()](#getShapeStyle--) | 도형의 스타일 객체를 반환합니다. |
| [getShapeType()](#getShapeType--) | 기하학 프리셋 유형을 반환하거나 설정합니다. |
| [setShapeType(int value)](#setShapeType-int-) | 기하학 프리셋 유형을 반환하거나 설정합니다. |
| [getAdjustments()](#getAdjustments--) | 도형의 조정값 컬렉션을 반환합니다. |
| [createShapeElements()](#createShapeElements--) | 도형 요소 배열을 생성하고 반환합니다. |

### getGeometryPaths() {#getGeometryPaths--}
```
public final IGeometryPath[] getGeometryPaths()
```

도형의 기하학적 경로 복사본을 반환합니다. 좌표는 도형의 왼쪽 상단 모서리를 기준으로 합니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape) pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      IGeometryPath geometryPath = shape.getGeometryPaths()[0];
>      geometryPath.lineTo(100, 50, 1);
>      geometryPath.lineTo(100, 50, 4);
>      shape.setGeometryPath(geometryPath);
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**  
com.aspose.slides.IGeometryPath[] - Array of [IGeometryPath](../../com.aspose.slides/igeometrypath)

### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public final void setGeometryPath(IGeometryPath geometryPath)
```

[IGeometryPath](../../com.aspose.slides/igeometrypath) 객체에서 도형의 기하학을 업데이트합니다. 좌표는 도형의 왼쪽 상단 모서리를 기준으로 해야 합니다. 도형 유형을 [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom)(ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int)))으로 변경합니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape) pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      GeometryPath geometryPath0 = new GeometryPath();
>      geometryPath0.moveTo(0, 0);
>      geometryPath0.lineTo(shape.getWidth(), 0);
>      geometryPath0.lineTo(shape.getWidth(), shape.getHeight()/3);
>      geometryPath0.lineTo(0, shape.getHeight() / 3);
>      geometryPath0.closeFigure();
>      GeometryPath geometryPath1 = new GeometryPath();
>      geometryPath1.moveTo(0, shape.getHeight()/3 * 2);
>      geometryPath1.lineTo(shape.getWidth(), shape.getHeight() / 3 * 2);
>      geometryPath1.lineTo(shape.getWidth(), shape.getHeight());
>      geometryPath1.lineTo(0, shape.getHeight());
>      geometryPath1.closeFigure();
>      shape.setGeometryPaths(new GeometryPath[] { geometryPath0, geometryPath1});
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | 기하학 경로 |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public final void setGeometryPaths(IGeometryPath[] geometryPaths)
```

[IGeometryPath](../../com.aspose.slides/igeometrypath) 배열에서 도형의 기하학을 업데이트합니다. 좌표는 도형의 왼쪽 상단 모서리를 기준으로 해야 합니다. 도형 유형을 [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom)(ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int)))으로 변경합니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape)pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      IGeometryPath geometryPath = shape.getGeometryPaths()[0];
>      geometryPath.lineTo(100, 50, 1);
>      geometryPath.lineTo(100, 50, 4);
>      shape.setGeometryPath(geometryPath);
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | 배열 기하학 경로 |

### getShapeStyle() {#getShapeStyle--}
```
public final IShapeStyle getShapeStyle()
```

도형의 스타일 객체를 반환합니다. 읽기 전용 [IShapeStyle](../../com.aspose.slides/ishapestyle).

**반환:**  
[IShapeStyle](../../com.aspose.slides/ishapestyle)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

기하학 프리셋 유형을 반환하거나 설정합니다. 참고: 값이 변경되면 모든 조정값이 기본값으로 재설정됩니다. 읽기/쓰기 [ShapeType](../../com.aspose.slides/shapetype).

**반환:**  
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

기하학 프리셋 유형을 반환하거나 설정합니다. 참고: 값이 변경되면 모든 조정값이 기본값으로 재설정됩니다. 읽기/쓰기 [ShapeType](../../com.aspose.slides/shapetype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public final IAdjustValueCollection getAdjustments()
```

도형의 조정값 컬렉션을 반환합니다. 읽기 전용 [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**반환:**  
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)

### createShapeElements() {#createShapeElements--}
```
public final IShapeElement[] createShapeElements()
```

도형 요소 배열을 생성하고 반환합니다.

**반환:**  
com.aspose.slides.IShapeElement[] - Array of [ShapeElement](../../com.aspose.slides/shapeelement)