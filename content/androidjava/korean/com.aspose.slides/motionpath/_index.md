---
title: MotionPath
second_title: Aspose.Slides for Android Java API 레퍼런스
description: 모션 경로를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/motionpath/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

모션 경로를 나타냅니다.
## 생성자

| Constructor | Description |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## 메서드

| Method | Description |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | 경로에 새 명령을 추가합니다 |
| [getCount()](#getCount--) | 컬렉션에 포함된 경로 수를 반환합니다. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | 경로에 새 명령을 삽입합니다 |
| [clear()](#clear--) | 컬렉션의 모든 명령을 제거합니다. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | 컬렉션에서 지정된 명령을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에 있는 명령을 제거합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 명령을 반환합니다. |
| [iterator()](#iterator--) | 컬렉션을 반복하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 이터레이터를 반환합니다. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public final IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


경로에 새 명령을 추가합니다

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | 포인트 배열 |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 상대 좌표 boolean |

**Returns:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


컬렉션에 포함된 경로 수를 반환합니다. 읽기 전용 int.

**Returns:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public final void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


경로에 새 명령을 삽입합니다

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 항목을 삽입할 0 기반 인덱스입니다. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | 포인트 배열 |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 상대 좌표 boolean |

### clear() {#clear--}
```
public final void clear()
```


컬렉션의 모든 명령을 제거합니다.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


컬렉션에서 지정된 명령을 제거합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | 제거할 모션 경로. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


지정된 인덱스에 있는 명령을 제거합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 삭제할 명령의 인덱스입니다. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


지정된 인덱스에 있는 명령을 반환합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 요소의 인덱스입니다. |

**Returns:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - The [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) 객체.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


컬렉션을 반복하는 열거자를 반환합니다.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - 컬렉션을 반복하는 데 사용할 수 있는 IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


전체 컬렉션에 대한 java 이터레이터를 반환합니다.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - 전체 컬렉션에 대한 java.util.Iterator.