---
title: IChartWall
second_title: Android용 Aspose.Slides Java API 참조
description: 3D 차트의 벽을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

3D 차트의 벽을 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [getThickness()](#getThickness--) | 플롯 볼륨의 가장 큰 차원의 백분율로 벽 두께를 반환하거나 설정합니다. |
| [setThickness(int value)](#setThickness-int-) | 플롯 볼륨의 가장 큰 차원의 백분율로 벽 두께를 반환하거나 설정합니다. |
| [getFormat()](#getFormat--) | 벽 채우기, 선, 효과, 3D 스타일을 반환합니다. |
| [getPictureType()](#getPictureType--) | 그림 유형을 반환하거나 설정합니다. |
| [setPictureType(int value)](#setPictureType-int-) | 그림 유형을 반환하거나 설정합니다. |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```

플롯 볼륨의 가장 큰 차원의 백분율로 벽 두께를 반환하거나 설정합니다. 읽기/쓰기 int.

**반환:**  
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```

플롯 볼륨의 가장 큰 차원의 백분율로 벽 두께를 반환하거나 설정합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

벽 채우기, 선, 효과, 3D 스타일을 반환합니다. 읽기 전용 [IFormat](../../com.aspose.slides/iformat).

**반환:**  
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```

그림 유형을 반환하거나 설정합니다. 읽기/쓰기 [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**반환:**  
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```

그림 유형을 반환하거나 설정합니다. 읽기/쓰기 [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |