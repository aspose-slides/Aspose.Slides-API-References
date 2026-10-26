---
title: IGeometryShape
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 모든 기하학적 도형의 부모 클래스를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/igeometryshape/
---
**All Implemented Interfaces:**  
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGeometryShape extends IShape
```

모든 기하학적 도형의 상위 클래스를 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | 기하학 도형의 경로 복사본을 반환합니다. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | [IGeometryPath](../../com.aspose.slides/igeometrypath) 객체를 사용하여 도형 기하학을 업데이트합니다. |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | 배열 [IGeometryPath](../../com.aspose.slides/igeometrypath)을 사용하여 도형 기하학을 업데이트합니다. |
| [getShapeStyle()](#getShapeStyle--) | 도형 스타일 객체를 반환합니다. |
| [getShapeType()](#getShapeType--) | 기하학 프리셋 유형을 반환하거나 설정합니다. |
| [setShapeType(int value)](#setShapeType-int-) | 기하학 프리셋 유형을 반환하거나 설정합니다. |
| [getAdjustments()](#getAdjustments--) | 도형 조정 값의 컬렉션을 반환합니다. |
| [createShapeElements()](#createShapeElements--) | 도형 요소 배열을 생성하고 반환합니다. |
### getGeometryPaths() {#getGeometryPaths--}
```
public abstract IGeometryPath[] getGeometryPaths()
```

기하학 도형의 경로 복사본을 반환합니다. 좌표는 도형의 왼쪽 상단 모서리를 기준으로 합니다.

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
com.aspose.slides.IGeometryPath[] - [IGeometryPath](../../com.aspose.slides/igeometrypath) 배열
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public abstract void setGeometryPath(IGeometryPath geometryPath)
```

[IGeometryPath](../../com.aspose.slides/igeometrypath) 객체를 사용하여 도형 기하학을 업데이트합니다. 좌표는 도형의 왼쪽 상단 모서리를 기준으로 해야 합니다. 도형 유형을 [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom)(ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int)))으로 변경합니다.

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | 기하학 경로 |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public abstract void setGeometryPaths(IGeometryPath[] geometryPaths)
```

[IGeometryPath](../../com.aspose.slides/igeometrypath) 배열을 사용하여 도형 기하학을 업데이트합니다. 좌표는 도형의 왼쪽 상단 모서리를 기준으로 해야 합니다. 도형 유형을 [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom)(ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int)))으로 변경합니다.

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | 배열 기하학 경로 |

### getShapeStyle() {#getShapeStyle--}
```
public abstract IShapeStyle getShapeStyle()
```

도형 스타일 객체를 반환합니다. 읽기 전용 [IShapeStyle](../../com.aspose.slides/ishapestyle).

**반환:**  
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public abstract int getShapeType()
```

기하학 프리셋 유형을 반환하거나 설정합니다. 참고: 값을 변경하면 모든 조정 값이 기본값으로 초기화됩니다. 읽기/쓰기 [ShapeType](../../com.aspose.slides/shapetype).

**반환:**  
int
### setShapeType(int value) {#setShapeType-int-}
```
public abstract void setShapeType(int value)
```

기하학 프리셋 유형을 반환하거나 설정합니다. 참고: 값을 변경하면 모든 조정 값이 기본값으로 초기화됩니다. 읽기/쓰기 [ShapeType](../../com.aspose.slides/shapetype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public abstract IAdjustValueCollection getAdjustments()
```

도형 조정 값의 컬렉션을 반환합니다. 읽기 전용 [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**반환:**  
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public abstract IShapeElement[] createShapeElements()
```

도형 요소 배열을 생성하고 반환합니다.

**반환:**  
com.aspose.slides.IShapeElement[] - [IShapeElement](../../com.aspose.slides/ishapeelement) 배열