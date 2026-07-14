---
title: IGroupShape
second_title: Java API 레퍼런스를 통한 Aspose.Slides for Android
description: 슬라이드의 도형 그룹을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/igroupshape/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGroupShape extends IShape
```

슬라이드의 도형 그룹을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getGroupShapeLock()](#getGroupShapeLock--) | Returns shape's locks. |
| [getShapes()](#getShapes--) | Returns the collection of shapes inside the group. |
### getGroupShapeLock() {#getGroupShapeLock--}
```
public abstract IGroupShapeLock getGroupShapeLock()
```


도형의 잠금 정보를 반환합니다. 읽기 전용 [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**반환값:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```


그룹 안에 포함된 도형 컬렉션을 반환합니다. 읽기 전용 [IShapeCollection](../../com.aspose.slides/ishapecollection).

**반환값:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)