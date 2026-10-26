---
title: PointCollection
second_title: Aspose.Slides for Android Java API 레퍼런스
description: 애니메이션 포인트의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/pointcollection/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

애니메이션 포인트 컬렉션을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCount()](#getCount--) | 컬렉션에 있는 포인트 수를 반환합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 포인트를 반환합니다. |
| [iterator()](#iterator--) | 컬렉션을 반복하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 반복자를 반환합니다. |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```


### getCount() {#getCount--}
```
public final int getCount()
```


컬렉션에 있는 포인트 수를 반환합니다. 읽기 전용 int.

**반환값:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```


지정된 인덱스에 있는 포인트를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 요소의 인덱스. |

**반환값:**
[IPoint](../../com.aspose.slides/ipoint) - [IPoint](../../com.aspose.slides/ipoint) 객체.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```


컬렉션을 반복하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - 컬렉션을 반복하는 데 사용할 수 있는 IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```


전체 컬렉션에 대한 java 반복자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - 전체 컬렉션에 대한 java.util.Iterator.