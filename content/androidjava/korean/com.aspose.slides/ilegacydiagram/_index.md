---
title: ILegacyDiagram
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 레거시 다이어그램 객체를 나타냅니다
type: docs
url: /ko/com.aspose.slides/ilegacydiagram/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

레거시 다이어그램 객체를 나타냅니다
## 메서드

| Method | Description |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | 레거시 다이어그램을 편집 가능한 SmartArt 객체로 변환합니다. |
| [convertToGroupShape()](#convertToGroupShape--) | 레거시 다이어그램을 편집 가능한 그룹 형상으로 변환합니다. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

레거시 다이어그램을 편집 가능한 SmartArt 객체로 변환합니다. 생성된 SmartArt 객체는 동일한 위치의 상위 그룹 형상에 추가됩니다.

**반환값:**
[ISmartArt](../../com.aspose.slides/ismartart) - 생성된 SmartArt 객체.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

레거시 다이어그램을 편집 가능한 그룹 형상으로 변환합니다. 생성된 GroupShape 객체는 동일한 위치의 상위 그룹 형상에 추가됩니다.

**반환값:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 생성된 GroupShape 객체.