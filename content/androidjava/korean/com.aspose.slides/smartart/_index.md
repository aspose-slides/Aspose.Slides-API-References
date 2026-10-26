---
title: SmartArt
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: SmartArt 다이어그램을 나타냅니다
type: docs
url: /ko/com.aspose.slides/smartart/
---
**상속:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**구현된 모든 인터페이스:**  
[com.aspose.slides.ISmartArt](../../com.aspose.slides/ismartart)  
```
public class SmartArt extends GraphicalObject implements ISmartArt
```

SmartArt 다이어그램을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | SmartArt 개체의 모든 노드 컬렉션을 반환합니다. |
| [getNodes()](#getNodes--) | SmartArt 개체의 루트 노드 컬렉션을 반환합니다. |
| [getLayout()](#getLayout--) | SmartArt 개체의 레이아웃을 반환하거나 설정합니다. |
| [setLayout(int value)](#setLayout-int-) | SmartArt 개체의 레이아웃을 반환하거나 설정합니다. |
| [getQuickStyle()](#getQuickStyle--) | SmartArt 개체의 빠른 스타일을 반환하거나 설정합니다. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | SmartArt 개체의 빠른 스타일을 반환하거나 설정합니다. |
| [getColorStyle()](#getColorStyle--) | SmartArt 개체의 색상 스타일을 반환하거나 설정합니다. |
| [setColorStyle(int value)](#setColorStyle-int-) | SmartArt 개체의 색상 스타일을 반환하거나 설정합니다. |
| [isReversed()](#isReversed--) | (다이어그램이 반전 기능을 지원하는 경우) SmartArt 다이어그램의 왼쪽에서 오른쪽(LTR) 또는 오른쪽에서 왼쪽(RTL) 방향 상태를 반환하거나 설정합니다. |
| [setReversed(boolean value)](#setReversed-boolean-) | (다이어그램이 반전 기능을 지원하는 경우) SmartArt 다이어그램의 왼쪽에서 오른쪽(LTR) 또는 오른쪽에서 왼쪽(RTL) 방향 상태를 반환하거나 설정합니다. |

### getAllNodes() {#getAllNodes--}
```
public final ISmartArtNodeCollection getAllNodes()
```

SmartArt 개체의 모든 노드 컬렉션을 반환합니다. 읽기 전용 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**반환값:**  
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getNodes() {#getNodes--}
```
public final ISmartArtNodeCollection getNodes()
```

SmartArt 개체의 루트 노드 컬렉션을 반환합니다. 읽기 전용 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**반환값:**  
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getLayout() {#getLayout--}
```
public final int getLayout()
```

SmartArt 개체의 레이아웃을 반환하거나 설정합니다. 읽기/쓰기 [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**반환값:**  
int

### setLayout(int value) {#setLayout-int-}
```
public final void setLayout(int value)
```

SmartArt 개체의 레이아웃을 반환하거나 설정합니다. 읽기/쓰기 [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public final int getQuickStyle()
```

SmartArt 개체의 빠른 스타일을 반환하거나 설정합니다. 읽기/쓰기 [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**반환값:**  
int

### setQuickStyle(int value) {#setQuickStyle-int-}
```
public final void setQuickStyle(int value)
```

SmartArt 개체의 빠른 스타일을 반환하거나 설정합니다. 읽기/쓰기 [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public final int getColorStyle()
```

SmartArt 개체의 색상 스타일을 반환하거나 설정합니다. 읽기/쓰기 [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**반환값:**  
int

### setColorStyle(int value) {#setColorStyle-int-}
```
public final void setColorStyle(int value)
```

SmartArt 개체의 색상 스타일을 반환하거나 설정합니다. 읽기/쓰기 [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public final boolean isReversed()
```

(다이어그램이 반전 기능을 지원하는 경우) SmartArt 다이어그램의 왼쪽에서 오른쪽(LTR) 또는 오른쪽에서 왼쪽(RTL) 방향 상태를 반환하거나 설정합니다. 읽기/쓰기 boolean.

**반환값:**  
boolean

### setReversed(boolean value) {#setReversed-boolean-}
```
public final void setReversed(boolean value)
```

(다이어그램이 반전 기능을 지원하는 경우) SmartArt 다이어그램의 왼쪽에서 오른쪽(LTR) 또는 오른쪽에서 왼쪽(RTL) 방향 상태를 반환하거나 설정합니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |