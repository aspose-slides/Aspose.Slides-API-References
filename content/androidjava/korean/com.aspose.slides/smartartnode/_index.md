---
title: SmartArtNode
second_title: Android용 Aspose.Slides Java API 참조
description: SmartArt 객체의 노드를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/smartartnode/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

SmartArt 개체의 노드를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | 현재 노드의 모든 자식 노드 컬렉션을 반환합니다. |
| [getShapes()](#getShapes--) | 노드와 연결된 모든 도형의 컬렉션을 반환합니다. |
| [getTextFrame()](#getTextFrame--) | 노드의 텍스트 프레임을 반환합니다. |
| [isAssistant()](#isAssistant--) | 노드를 어시스턴트로 설정하거나 반환합니다. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | 노드를 어시스턴트로 설정하거나 반환합니다. |
| [getLevel()](#getLevel--) | 노드의 중첩 레벨을 반환합니다. |
| [getBulletFillFormat()](#getBulletFillFormat--) | 노드 글머리 기호의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. |
| [getPosition()](#getPosition--) | 형제 노드 중에서 노드의 0 기반 위치를 반환하거나 설정합니다. |
| [setPosition(int value)](#setPosition-int-) | 형제 노드 중에서 노드의 0 기반 위치를 반환하거나 설정합니다. |
| [isHidden()](#isHidden--) | 이 노드가 데이터 모델에서 숨겨진 노드인 경우 true를 반환합니다. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | 현재 노드와 연결된 조직도 레이아웃 유형을 반환하거나 설정합니다. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | 현재 노드와 연결된 조직도 레이아웃 유형을 반환하거나 설정합니다. |
| [remove()](#remove--) | 현재 노드를 제거합니다. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```


현재 노드의 모든 자식 노드 컬렉션을 반환합니다. 읽기 전용 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**반환값:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```


노드와 연결된 모든 도형의 컬렉션을 반환합니다. 읽기 전용 [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**반환값:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


노드의 텍스트 프레임을 반환합니다. 읽기 전용 [ITextFrame](../../com.aspose.slides/itextframe).

**반환값:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```


노드를 어시스턴트로 설정하거나 반환합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```


노드를 어시스턴트로 설정하거나 반환합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```


노드의 중첩 레벨을 반환합니다. 읽기 전용 int.

**반환값:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```


노드 글머리 기호의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. 참고: 일부 SmartArt 레이아웃 유형에서는 노드에 글머리 기호를 제공하지 않아 null을 반환할 수 있습니다. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

**반환값:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


형제 노드 중에서 노드의 0 기반 위치를 반환하거나 설정합니다. 읽기/쓰기 int .

**반환값:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


형제 노드 중에서 노드의 0 기반 위치를 반환하거나 설정합니다. 읽기/쓰기 int .

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```


데이터 모델에서 이 노드가 숨겨진 노드인 경우 true를 반환합니다. 읽기 전용 boolean.

**반환값:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```


현재 노드와 연결된 조직도 레이아웃 유형을 반환하거나 설정합니다. 읽기/쓰기 [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**반환값:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```


현재 노드와 연결된 조직도 레이아웃 유형을 반환하거나 설정합니다. 읽기/쓰기 [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```


현재 노드를 제거합니다.

**반환값:**
boolean - 제거에 성공하면 true, 그렇지 않으면 false