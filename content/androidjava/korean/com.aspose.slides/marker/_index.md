---
title: Marker
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 차트의 마커를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/marker/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IMarker](../../com.aspose.slides/imarker), com.aspose.slides.IDOMObject  
```
public class Marker implements IMarker, IDOMObject
```

차트 마커를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSymbol()](#getSymbol--) | 라인 차트, 스캐터 차트 또는 레이더 차트의 마커 스타일을 나타냅니다. |
| [setSymbol(int value)](#setSymbol-int-) | 라인 차트, 스캐터 차트 또는 레이더 차트의 마커 스타일을 나타냅니다. |
| [getFormat()](#getFormat--) | 마커 채우기를 가져오거나 설정합니다. |
| [getSize()](#getSize--) | 라인 차트, 스캐터 차트 또는 레이더 차트의 마커 크기를 나타냅니다. |
| [setSize(int value)](#setSize-int-) | 라인 차트, 스캐터 차트 또는 레이더 차트의 마커 크기를 나타냅니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getSymbol() {#getSymbol--}
```
public final int getSymbol()
```

라인 차트, 스캐터 차트 또는 레이더 차트의 마커 스타일을 나타냅니다. 읽기/쓰기 [MarkerStyleType](../../com.aspose.slides/markerstyletype).

**반환:**  
int

### setSymbol(int value) {#setSymbol-int-}
```
public final void setSymbol(int value)
```

라인 차트, 스캐터 차트 또는 레이더 차트의 마커 스타일을 나타냅니다. 읽기/쓰기 [MarkerStyleType](../../com.aspose.slides/markerstyletype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

마커 채우기를 가져오거나 설정합니다. 읽기 전용 [IFormat](../../com.aspose.slides/iformat).

**반환:**  
[IFormat](../../com.aspose.slides/iformat)

### getSize() {#getSize--}
```
public final int getSize()
```

라인 차트, 스캐터 차트 또는 레이더 차트의 마커 크기를 나타냅니다. 읽기/쓰기 int.

**반환:**  
int

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```

라인 차트, 스캐터 차트 또는 레이더 차트의 마커 크기를 나타냅니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**  
com.aspose.slides.IDOMObject