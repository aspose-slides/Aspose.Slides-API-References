---
title: LegacyDiagram
second_title: Aspose.Slides for Java API 레퍼런스
description: 레거시 다이어그램 개체를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/legacydiagram/
---
**상속:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**구현된 모든 인터페이스:**  
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)  
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

레거시 다이어그램 개체를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | 레거시 다이어그램을 편집 가능한 SmartArt 개체로 변환합니다. |
| [convertToGroupShape()](#convertToGroupShape--) | 레거시 다이어그램을 편집 가능한 그룹 모양으로 변환합니다. |

### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```

레거시 다이어그램을 편집 가능한 SmartArt 개체로 변환합니다. 생성된 SmartArt 개체는 동일한 위치의 상위 그룹 모양에 추가됩니다.

**반환:**  
[ISmartArt](../../com.aspose.slides/ismartart) - 생성된 SmartArt 개체.

### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```

레거시 다이어그램을 편집 가능한 그룹 모양으로 변환합니다. 생성된 GroupShape 개체는 동일한 위치의 상위 그룹 모양에 추가됩니다.

**반환:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - 생성된 GroupShape 개체.