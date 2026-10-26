---
title: IPointCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 부분들의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ipointcollection/
---
**모든 구현된 인터페이스:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPointCollection extends System.Collections.Generic.IGenericEnumerable<IPoint>
```

부분들의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCount()](#getCount--) | 컬렉션에 포함된 포인트의 수를 반환합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 포인트를 반환합니다. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

컬렉션에 포함된 포인트의 수를 반환합니다. 읽기 전용 int.

**반환:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IPoint get_Item(int index)
```

지정된 인덱스의 포인트를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 요소의 인덱스. |

**반환:**
[IPoint](../../com.aspose.slides/ipoint) - [IPoint](../../com.aspose.slides/ipoint) 객체.