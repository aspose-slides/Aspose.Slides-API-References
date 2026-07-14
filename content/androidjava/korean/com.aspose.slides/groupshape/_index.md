---
title: GroupShape
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 슬라이드에 있는 도형 그룹을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/groupshape/
---
**상속:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)  
```
public class GroupShape extends Shape implements IGroupShape
```

슬라이드에 있는 도형 그룹을 나타냅니다.  
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | 도형에 대한 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다. |
| [getGroupShapeLock()](#getGroupShapeLock--) | 도형의 잠금을 반환합니다. |
| [getShapes()](#getShapes--) | 그룹 내부의 도형 컬렉션을 반환합니다. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```


도형에 대한 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다. 참고: GroupShape 객체는 선 속성이 없으므로 null을 반환합니다. 읽기 전용 [ILineFormat](../../com.aspose.slides/ilineformat).

**반환:**  
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```


도형의 잠금을 반환합니다. 읽기 전용 [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**반환:**  
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


그룹 내부의 도형 컬렉션을 반환합니다. 읽기 전용 [IShapeCollection](../../com.aspose.slides/ishapecollection).

**반환:**  
[IShapeCollection](../../com.aspose.slides/ishapecollection)