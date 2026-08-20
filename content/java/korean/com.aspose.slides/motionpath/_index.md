---
title: MotionPath
second_title: Aspose.Slides Java API 레퍼런스
description: 모션 경로를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/motionpath/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

모션 경로를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | 경로에 새 명령을 추가합니다. |
| [getCount()](#getCount--) | 컬렉션에 있는 경로 수를 반환합니다. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | 경로에 새 명령을 삽입합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 명령을 제거합니다. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | 컬렉션에서 지정된 명령을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스의 명령을 제거합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 명령을 반환합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java iterator를 반환합니다. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


경로에 새 명령를 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | 점 배열 |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Relative coordinates boolean |

**반환값:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


컬렉션에 있는 경로 수를 반환합니다. 읽기 전용 int.

**반환값:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


경로에 새 명령을 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 삽입해야 하는 항목의 0부터 시작하는 인덱스. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | 점 배열 |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Relative coordinates boolean |

### clear() {#clear--}
```
public final void clear()
```


컬렉션에서 모든 명령을 제거합니다.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


컬렉션에서 지정된 명령을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | 제거할 모션 경로. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


지정된 인덱스의 명령을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 삭제해야 하는 명령의 인덱스. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


지정된 인덱스의 명령을 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 요소의 인덱스. |

**반환값:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) 객체.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


컬렉션을 순회하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


전체 컬렉션에 대한 java iterator를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - An java.util.Iterator for the entire collection.