---
title: ISmartArt
second_title: Aspose.Slides for Java API 참조
description: SmartArt 다이어그램을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ismartart/
---
**전체 구현된 인터페이스:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

SmartArt 다이어그램을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | SmartArt 객체의 모든 노드 컬렉션을 반환합니다. |
| [getNodes()](#getNodes--) | SmartArt 객체의 루트 노드 컬렉션을 반환합니다. |
| [getLayout()](#getLayout--) | SmartArt 객체의 레이아웃을 반환하거나 설정합니다. |
| [setLayout(int value)](#setLayout-int-) | SmartArt 객체의 레이아웃을 반환하거나 설정합니다. |
| [getQuickStyle()](#getQuickStyle--) | SmartArt 객체의 빠른 스타일을 반환하거나 설정합니다. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | SmartArt 객체의 빠른 스타일을 반환하거나 설정합니다. |
| [getColorStyle()](#getColorStyle--) | SmartArt 객체의 색상 스타일을 반환하거나 설정합니다. |
| [setColorStyle(int value)](#setColorStyle-int-) | SmartArt 객체의 색상 스타일을 반환하거나 설정합니다. |
| [isReversed()](#isReversed--) | 다이어그램이 역전(왼쪽에서 오른쪽(LTR) 또는 오른쪽에서 왼쪽(RTL))을 지원하는 경우, SmartArt 다이어그램의 상태를 반환하거나 설정합니다. |
| [setReversed(boolean value)](#setReversed-boolean-) | 다이어그램이 역전(왼쪽에서 오른쪽(LTR) 또는 오른쪽에서 왼쪽(RTL))을 지원하는 경우, SmartArt 다이어그램의 상태를 반환하거나 설정합니다. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

SmartArt 객체의 모든 노드 컬렉션을 반환합니다. 읽기 전용 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**반환:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

SmartArt 객체의 루트 노드 컬렉션을 반환합니다. 읽기 전용 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**반환:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

SmartArt 객체의 레이아웃을 반환하거나 설정합니다. 읽기/쓰기 [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**반환:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

SmartArt 객체의 레이아웃을 반환하거나 설정합니다. 읽기/쓰기 [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |
### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

SmartArt 객체의 빠른 스타일을 반환하거나 설정합니다. 읽기/쓰기 [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**반환:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```

SmartArt 객체의 빠른 스타일을 반환하거나 설정합니다. 읽기/쓰기 [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |
### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

SmartArt 객체의 색상 스타일을 반환하거나 설정합니다. 읽기/쓰기 [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**반환:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

SmartArt 객체의 색상 스타일을 반환하거나 설정합니다. 읽기/쓰기 [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |
### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

다이어그램이 역전(왼쪽에서 오른쪽(LTR) 또는 오른쪽에서 왼쪽(RTL))을 지원하는 경우, SmartArt 다이어그램의 상태를 반환하거나 설정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

다이어그램이 역전(왼쪽에서 오른쪽(LTR) 및 오른쪽에서 왼쪽(RTL))을 지원하는 경우, SmartArt 다이어그램의 상태를 반환하거나 설정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |