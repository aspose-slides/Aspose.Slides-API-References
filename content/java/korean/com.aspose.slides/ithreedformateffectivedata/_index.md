---
title: IThreeDFormatEffectiveData
second_title: Java용 Aspose.Slides API 레퍼런스
description: 유효한 3-D 서식 속성을 나타내는 불변 객체.
type: docs
url: /ko/com.aspose.slides/ithreedformateffectivedata/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

유효한 3-D 서식 속성을 나타내는 불변 객체.

--------------------

이 인터페이스는 [IThreeDFormat](../../com.aspose.slides/ithreedformat) 인터페이스와 함께 사용되어 상속이 적용된 유효한 서식 값을 반환합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | 3D 윤곽선의 너비를 반환합니다. |
| [getExtrusionHeight()](#getExtrusionHeight--) | 돌출 효과의 높이를 반환합니다. |
| [getDepth()](#getDepth--) | 3D 형태의 깊이를 반환합니다. |
| [getBevelTop()](#getBevelTop--) | 상위 3D 베벨의 유형을 반환합니다. |
| [getBevelBottom()](#getBevelBottom--) | 하위 3D 베벨의 유형을 반환합니다. |
| [getContourColor()](#getContourColor--) | 윤곽선의 색상을 반환합니다. |
| [getExtrusionColor()](#getExtrusionColor--) | 돌출의 색상을 반환합니다. |
| [getCamera()](#getCamera--) | 카메라 설정을 반환합니다. |
| [getLightRig()](#getLightRig--) | 빛 유형을 반환합니다. |
| [getMaterial()](#getMaterial--) | 재질 유형을 반환합니다. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


3D 윤곽선의 너비를 반환합니다. 읽기 전용 double.

**반환:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


돌출 효과의 높이를 반환합니다. 읽기 전용 double.

**반환:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


3D 형태의 깊이를 반환합니다. 읽기 전용 double.

**반환:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```


상위 3D 베벨의 유형을 반환합니다. 읽기 전용 [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**반환:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```


하위 3D 베벨의 유형을 반환합니다. 읽기 전용 [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**반환:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Color getContourColor()
```


윤곽선의 색상을 반환합니다. 읽기 전용 java.awt.Color.

**반환:**
java.awt.Color
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Color getExtrusionColor()
```


돌출의 색상을 반환합니다. 읽기 전용 java.awt.Color.

**반환:**
java.awt.Color
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```


카메라 설정을 반환합니다. 읽기 전용 [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**반환:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```


빛 유형을 반환합니다. 읽기 전용 [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**반환:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


재질 유형을 반환합니다. 읽기 전용 [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**반환:**
int