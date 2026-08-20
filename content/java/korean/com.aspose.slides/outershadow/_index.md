---
title: OuterShadow
second_title: Aspose.Slides for Java API 참조
description: 외부 그림자 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/outershadow/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IOuterShadow](../../com.aspose.slides/ioutershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class OuterShadow implements IOuterShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

외부 그림자 효과를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | 포인트 단위의 블러 반경. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | 포인트 단위의 블러 반경. |
| [getDirection()](#getDirection--) | 그림자 방향, 각도 단위. |
| [setDirection(float value)](#setDirection-float-) | 그림자 방향, 각도 단위. |
| [getDistance()](#getDistance--) | 객체로부터 그림자의 거리, 포인트 단위. |
| [setDistance(double value)](#setDistance-double-) | 객체로부터 그림자의 거리, 포인트 단위. |
| [getShadowColor()](#getShadowColor--) | 그림자의 색상. |
| [getRectangleAlign()](#getRectangleAlign--) | 사각형 정렬. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | 사각형 정렬. |
| [getSkewHorizontal()](#getSkewHorizontal--) | 수평 비스듬 각도, 각도 단위. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | 수평 비스듬 각도, 각도 단위. |
| [getSkewVertical()](#getSkewVertical--) | 수직 비스듬 각도, 각도 단위. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | 수직 비스듬 각도, 각도 단위. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 그림자와 모양이 함께 회전하는지 여부를 나타냅니다. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | 그림자와 모양이 함께 회전하는지 여부를 나타냅니다. |
| [getScaleHorizontal()](#getScaleHorizontal--) | 원본 크기의 백분율로 표시되는 수평 스케일링 계수. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | 원본 크기의 백분율로 표시되는 수평 스케일링 계수. |
| [getScaleVertical()](#getScaleVertical--) | 원본 크기의 백분율로 표시되는 수직 스케일링 계수. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | 원본 크기의 백분율로 표시되는 수직 스케일링 계수. |
| [getEffective()](#getEffective--) | 상속이 적용된 실제 외부 그림자 효과 데이터를 가져옵니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [OuterShadow](../../com.aspose.slides/outershadow)가 현재 [OuterShadow](../../com.aspose.slides/outershadow)와 동일한지 여부를 확인합니다. |
| [hashCode()](#hashCode--) | 특정 형식에 대한 해시 함수 역할을 합니다. |
### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

포인트 단위의 블러 반경. 기본값 - 0 pt. 읽기/쓰기 double.

**반환값:**  
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

포인트 단위의 블러 반경. 기본값 - 0 pt. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

그림자 방향, 각도 단위. 기본값 - 0 � (left-to-right). 읽기/쓰기 float.

**반환값:**  
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

그림자 방향, 각도 단위. 기본값 - 0 � (left-to-right). 읽기/쓰기 float.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

객체로부터 그림자의 거리, 포인트 단위. 기본값 - 0 pt. 읽기/쓰기 double.

**반환값:**  
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

객체로부터 그림자의 거리, 포인트 단위. 기본값 - 0 pt. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

그림자의 색상. 기본값 - 자동 검정(테마 의존). 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환값:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

사각형 정렬. 기본값 - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). 읽기/쓰기 [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**반환값:**  
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

사각형 정렬. 기본값 - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). 읽기/쓰기 [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

수평 비스듬 각도, 각도 단위. 기본값 - 0 �. 읽기/쓰기 double.

**반환값:**  
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

수평 비스듬 각도, 각도 단위. 기본값 - 0 �. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

수직 비스듬 각도, 각도 단위. 기본값 - 0 �. 읽기/쓰기 double.

**반환값:**  
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

수직 비스듬 각도, 각도 단위. 기본값 - 0 �. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

그림자와 모양이 함께 회전하는지 여부를 나타냅니다. 기본값 - true. 읽기/쓰기 boolean.

**반환값:**  
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

그림자와 모양이 함께 회전하는지 여부를 나타냅니다. 기본값 - true. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

원본 크기의 백분율로 표시되는 수평 스케일링 계수. 음수 스케일링은 뒤집힘을 발생시킵니다. 기본값 - 100 %. 읽기/쓰기 double.

**반환값:**  
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

원본 크기의 백분율로 표시되는 수평 스케일링 계수. 음수 스케일링은 뒤집힘을 발생시킵니다. 기본값 - 100 %. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

원본 크기의 백분율로 표시되는 수직 스케일링 계수. 음수 스케일링은 뒤집힘을 발생시킵니다. 기본값 - 100 %. 읽기/쓰기 double.

**반환값:**  
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

원본 크기의 백분율로 표시되는 수직 스케일링 계수. 음수 스케일링은 뒤집힘을 발생시킵니다. 기본값 - 100 %. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |
### getEffective() {#getEffective--}
```
public final IOuterShadowEffectiveData getEffective()
```

상속이 적용된 실제 외부 그림자 효과 데이터를 가져옵니다.

**반환값:**  
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata) - A [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**  
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

버전. 읽기 전용 long.

**반환값:**  
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

부모 IPresentationComponent를 반환합니다. 읽기 전용 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**반환값:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 [OuterShadow](../../com.aspose.slides/outershadow)가 현재 [OuterShadow](../../com.aspose.slides/outershadow)와 동일한지 여부를 확인합니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [OuterShadow](../../com.aspose.slides/outershadow). |

**반환값:**  
boolean - 객체가 동일하면 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 형식에 대한 해시 함수 역할을 합니다.

**반환값:**  
int - 현재 객체에 대한 해시 코드.