---
title: IMarker
second_title: Aspose.Slides for Android via Java API 참고 문서
description: 차트의 마커를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/imarker/
---```
public interface IMarker
```

차트의 마커를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSymbol()](#getSymbol--) | 선 차트, 산점도 차트 또는 레이더 차트에서 마커 스타일을 나타냅니다. |
| [setSymbol(int value)](#setSymbol-int-) | 선 차트, 산점도 차트 또는 레이더 차트에서 마커 스타일을 나타냅니다. |
| [getFormat()](#getFormat--) | 마커 채우기를 가져옵니다. |
| [getSize()](#getSize--) | 선 차트, 산점도 차트 또는 레이더 차트에서 마커 크기를 나타냅니다. |
| [setSize(int value)](#setSize-int-) | 선 차트, 산점도 차트 또는 레이더 차트에서 마커 크기를 나타냅니다. |
### getSymbol() {#getSymbol--}
```
public abstract int getSymbol()
```

선 차트, 산점도 차트 또는 레이더 차트에서 마커 스타일을 나타냅니다. 읽기/쓰기 [MarkerStyleType](../../com.aspose.slides/markerstyletype).

**반환:**
int
### setSymbol(int value) {#setSymbol-int-}
```
public abstract void setSymbol(int value)
```

선 차트, 산점도 차트 또는 레이더 차트에서 마커 스타일을 나타냅니다. 읽기/쓰기 [MarkerStyleType](../../com.aspose.slides/markerstyletype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

마커 채우기를 가져옵니다. 읽기 전용 [IFormat](../../com.aspose.slides/iformat).

**반환:**
[IFormat](../../com.aspose.slides/iformat)
### getSize() {#getSize--}
```
public abstract int getSize()
```

선 차트, 산점도 차트 또는 레이더 차트에서 마커 크기를 나타냅니다. 읽기/쓰기 int.

**반환:**
int
### setSize(int value) {#setSize-int-}
```
public abstract void setSize(int value)
```

선 차트, 산점도 차트 또는 레이더 차트에서 마커 크기를 나타냅니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |