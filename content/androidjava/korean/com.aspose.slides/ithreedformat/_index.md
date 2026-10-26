---
title: IThreeDFormat
second_title: Aspose.Slides for Android Java API 레퍼런스
description: 3-D 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ithreedformat/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

3-D 속성을 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | 3D 등고선의 너비를 반환하거나 설정합니다. |
| [setContourWidth(double value)](#setContourWidth-double-) | 3D 등고선의 너비를 반환하거나 설정합니다. |
| [getExtrusionHeight()](#getExtrusionHeight--) | 돌출 효과의 높이를 반환하거나 설정합니다. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | 돌출 효과의 높이를 반환하거나 설정합니다. |
| [getDepth()](#getDepth--) | 3D 모양의 깊이를 반환하거나 설정합니다. |
| [setDepth(double value)](#setDepth-double-) | 3D 모양의 깊이를 반환하거나 설정합니다. |
| [getBevelTop()](#getBevelTop--) | 상단 3D 베벨의 유형을 반환하거나 설정합니다. |
| [getBevelBottom()](#getBevelBottom--) | 하단 3D 베벨의 유형을 반환하거나 설정합니다. |
| [getContourColor()](#getContourColor--) | 등고선의 색상을 반환하거나 설정합니다. |
| [getExtrusionColor()](#getExtrusionColor--) | 돌출의 색상을 반환하거나 설정합니다. |
| [getCamera()](#getCamera--) | 카메라 설정을 반환하거나 설정합니다. |
| [getLightRig()](#getLightRig--) | 조명의 유형을 반환하거나 설정합니다. |
| [getMaterial()](#getMaterial--) | 재료의 유형을 반환하거나 설정합니다. |
| [setMaterial(int value)](#setMaterial-int-) | 재료의 유형을 반환하거나 설정합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 3-D 서식 데이터를 가져옵니다. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

3D 등고선의 너비를 반환하거나 설정합니다. Read/write double.

**반환:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

3D 등고선의 너비를 반환하거나 설정합니다. Read/write double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

돌출 효과의 높이를 반환하거나 설정합니다. Read/write double.

**반환:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

돌출 효과의 높이를 반환하거나 설정합니다. Read/write double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

3D 모양의 깊이를 반환하거나 설정합니다. Read/write double.

**반환:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

3D 모양의 깊이를 반환하거나 설정합니다. Read/write double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

상단 3D 베벨의 유형을 반환하거나 설정합니다. Read-only [IShapeBevel](../../com.aspose.slides/ishapebevel).

**반환:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

하단 3D 베벨의 유형을 반환하거나 설정합니다. Read-only [IShapeBevel](../../com.aspose.slides/ishapebevel).

**반환:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

등고선의 색상을 반환하거나 설정합니다. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

돌출의 색상을 반환하거나 설정합니다. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

카메라 설정을 반환하거나 설정합니다. Read-only [ICamera](../../com.aspose.slides/icamera).

**반환:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

조명의 유형을 반환하거나 설정합니다. Read-only [ILightRig](../../com.aspose.slides/ilightrig).

**반환:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

재료의 유형을 반환하거나 설정합니다. Read/write [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**반환:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

재료의 유형을 반환하거나 설정합니다. Read/write [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

상속이 적용된 효과적인 3-D 서식 데이터를 가져옵니다.

**반환:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).