---
title: ISmartArtNode
second_title: Aspose.Slides for Android via Java API Reference
description: SmartArt 다이어그램의 노드를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

SmartArt 다이어그램의 노드를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | 현재 노드의 모든 자식 노드 컬렉션을 반환합니다. |
| [getShapes()](#getShapes--) | 노드와 연결된 모든 도형 컬렉션을 반환합니다. |
| [getTextFrame()](#getTextFrame--) | 노드의 텍스트를 반환하거나 설정합니다. |
| [isAssistant()](#isAssistant--) | 노드를 어시스턴트로 반환하거나 설정합니다. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | 노드를 어시스턴트로 반환하거나 설정합니다. |
| [getLevel()](#getLevel--) | 노드의 중첩 수준을 반환합니다. |
| [getBulletFillFormat()](#getBulletFillFormat--) | 노드 글머리표에 대한 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. |
| [getPosition()](#getPosition--) | 형제 노드 중 노드의 0부터 시작하는 위치를 반환하거나 설정합니다. |
| [setPosition(int value)](#setPosition-int-) | 형제 노드 중 노드의 0부터 시작하는 위치를 반환하거나 설정합니다. |
| [isHidden()](#isHidden--) | 이 노드가 데이터 모델에서 숨겨진 노드인 경우 true를 반환합니다. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | 현재 노드와 연결된 조직도 레이아웃 유형을 반환하거나 설정합니다. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | 현재 노드와 연결된 조직도 레이아웃 유형을 반환하거나 설정합니다. |
| [remove()](#remove--) | 현재 노드를 제거합니다. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

현재 노드의 모든 자식 노드 컬렉션을 반환합니다. 읽기 전용 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**반환:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

노드와 연결된 모든 도형 컬렉션을 반환합니다. 읽기 전용 [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**반환:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

노드의 텍스트를 반환하거나 설정합니다. 읽기 전용 [ITextFrame](../../com.aspose.slides/itextframe).

**반환:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

노드를 어시스턴트로 반환하거나 설정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

노드를 어시스턴트로 반환하거나 설정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

노드의 중첩 수준을 반환합니다. 읽기 전용 int.

**반환:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

노드 글머리표에 대한 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. Note: can return null for certain types of SmartArt layout which does not provide bullets for nodes. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

**반환:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

형제 노드 중 노드의 0부터 시작하는 위치를 반환하거나 설정합니다. 읽기/쓰기 int.

**반환:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

형제 노드 중 노드의 0부터 시작하는 위치를 반환하거나 설정합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

이 노드가 데이터 모델에서 숨겨진 노드인 경우 true를 반환합니다. 읽기 전용 boolean.

**반환:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

현재 노드와 연결된 조직도 레이아웃 유형을 반환하거나 설정합니다. 읽기/쓰기 [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**반환:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

현재 노드와 연결된 조직도 레이아웃 유형을 반환하거나 설정합니다. 읽기/쓰기 [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

현재 노드를 제거합니다.

**반환:**
boolean - 성공적으로 제거되면 true, 그렇지 않으면 false.