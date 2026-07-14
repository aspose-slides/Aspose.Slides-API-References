---
title: IMotionPath
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 모션 경로를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/imotionpath/
---
**구현된 모든 인터페이스:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

모션 경로를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | 경로에 새로운 명령을 추가합니다 |
| [getCount()](#getCount--) | 컬렉션에 있는 경로 수를 반환합니다. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | 경로에 새로운 명령을 삽입합니다 |
| [clear()](#clear--) | 컬렉션의 모든 명령을 제거합니다. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | 컬렉션에서 지정된 명령을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스의 명령을 제거합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 명령을 반환합니다. |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

경로에 새로운 명령을 추가합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | int | 애니메이션 모션 효과 동작을 위한 명령 유형 [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | 포인트 배열 android.graphics.PointF[] |
| ptsType | int | 모션 경로의 포인트 유형 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 상대 좌표를 사용할지 여부를 나타냅니다 boolean |

**Returns:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - 경로의 명령 [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

컬렉션에 있는 경로 수를 반환합니다. 읽기 전용 int.

**Returns:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

경로에 새로운 명령을 삽입합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 명령 삽입을 위한 인덱스 int |
| type | int | 명령 유형 [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | 포인트 배열 android.graphics.PointF[] |
| ptsType | int | 모션 경로의 포인트 유형 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 상대 좌표를 사용할지 여부를 나타냅니다 boolean |
### clear() {#clear--}
```
public abstract void clear()
```

컬렉션의 모든 명령을 제거합니다.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```

컬렉션에서 지정된 명령을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | 제거할 모션 경로 [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

지정된 인덱스의 명령을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 명령을 제거할 인덱스 int |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

지정된 인덱스의 명령을 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 요소의 인덱스. |

**Returns:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - 지정된 인덱스의 명령 [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)