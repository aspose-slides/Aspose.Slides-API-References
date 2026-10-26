---
title: IGroupShape
second_title: Aspose.Slides for Java API 레퍼런스
description: 슬라이드의 도형 그룹을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/igroupshape/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGroupShape extends IShape
```

슬라이드의 도형 그룹을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getGroupShapeLock()](#getGroupShapeLock--) | 도형의 잠금을 반환합니다. |
| [getShapes()](#getShapes--) | 그룹 안의 도형 컬렉션을 반환합니다. |
### getGroupShapeLock() {#getGroupShapeLock--}
```
public abstract IGroupShapeLock getGroupShapeLock()
```

도형의 잠금을 반환합니다. 읽기 전용 [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**반환:**  
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

그룹 안의 도형 컬렉션을 반환합니다. 읽기 전용 [IShapeCollection](../../com.aspose.slides/ishapecollection).

**반환:**  
[IShapeCollection](../../com.aspose.slides/ishapecollection)