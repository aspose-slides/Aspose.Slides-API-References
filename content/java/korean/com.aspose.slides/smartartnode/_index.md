---
title: SmartArtNode
second_title: Aspose.Slides Java API 레퍼런스
description: SmartArt 개체의 노드를 나타냅니다
type: docs
url: /ko/com.aspose.slides/smartartnode/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

SmartArt 개체의 노드를 나타냅니다
## Methods

| Method | Description |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | 현재 노드의 모든 하위 노드 컬렉션을 반환합니다. |
| [getShapes()](#getShapes--) | 노드와 연결된 모든 도형 컬렉션을 반환합니다. |
| [getTextFrame()](#getTextFrame--) | 노드의 텍스트 프레임을 반환합니다. |
| [isAssistant()](#isAssistant--) | 노드를 보조 역할로 설정하거나 반환합니다. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | 노드를 보조 역할로 설정하거나 반환합니다. |
| [getLevel()](#getLevel--) | 노드의 중첩 수준을 반환합니다. |
| [getBulletFillFormat()](#getBulletFillFormat--) | 노드 글머리표에 대한 채우기 서식 속성을 포함하는 FillFormat 개체를 반환합니다. |
| [getPosition()](#getPosition--) | 형제 노드 중에서 노드의 0 기반 위치를 설정하거나 반환합니다. |
| [setPosition(int value)](#setPosition-int-) | 형제 노드 중에서 노드의 0 기반 위치를 설정하거나 반환합니다. |
| [isHidden()](#isHidden--) | 데이터 모델에서 이 노드가 숨김 노드이면 true를 반환합니다. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | 현재 노드와 연결된 조직도 레이아웃 유형을 설정하거나 반환합니다. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | 현재 노드와 연결된 조직도 레이아웃 유형을 설정하거나 반환합니다. |
| [remove()](#remove--) | 현재 노드를 삭제합니다. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

현재 노드의 모든 하위 노드 컬렉션을 반환합니다. 읽기 전용 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Returns:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

노드와 연결된 모든 도형 컬렉션을 반환합니다. 읽기 전용 [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Returns:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

노드의 텍스트 프레임을 반환합니다. 읽기 전용 [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

노드를 보조 역할로 설정하거나 반환합니다. 읽기/쓰기 boolean.

**Returns:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

노드를 보조 역할로 설정하거나 반환합니다. 읽기/쓰기 boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```

노드의 중첩 수준을 반환합니다. 읽기 전용 int.

**Returns:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

노드 글머리표에 대한 채우기 서식 속성을 포함하는 FillFormat 개체를 반환합니다. 참고: 글머리표를 제공하지 않는 특정 SmartArt 레이아웃 유형의 경우 null을 반환할 수 있습니다. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

형제 노드 중에서 노드의 0 기반 위치를 설정하거나 반환합니다. 읽기/쓰기 int.

**Returns:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

형제 노드 중에서 노드의 0 기반 위치를 설정하거나 반환합니다. 읽기/쓰기 int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

데이터 모델에서 이 노드가 숨김 노드이면 true를 반환합니다. 읽기 전용 boolean.

**Returns:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

현재 노드와 연결된 조직도 레이아웃 유형을 설정하거나 반환합니다. 읽기/쓰기 [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Returns:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

현재 노드와 연결된 조직도 레이아웃 유형을 설정하거나 반환합니다. 읽기/쓰기 [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```

현재 노드를 삭제합니다.

**Returns:**
boolean - 제거가 성공하면 true를 반환하고, 그렇지 않으면 false를 반환합니다