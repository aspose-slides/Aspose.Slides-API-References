---
title: GradientStopEffectiveData
second_title: Aspose.Slides for Java API 레퍼런스
description: 그라디언트 스톱을 나타내는 불변 객체입니다.
type: docs
url: /ko/com.aspose.slides/gradientstopeffectivedata/
---
**상속:**  
java.lang.Object

**모든 구현 인터페이스:**  
com.aspose.slides.IEffectiveData, [com.aspose.slides.IGradientStopEffectiveData](../../com.aspose.slides/igradientstopeffectivedata)  
```
public class GradientStopEffectiveData implements IEffectiveData, IGradientStopEffectiveData
```

그라디언트 스톱을 나타내는 불변 객체입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPosition()](#getPosition--) | 그라디언트 스톱의 위치(0..1)를 반환합니다. |
| [getColor()](#getColor--) | 그라디언트 스톱의 색상을 반환합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [GradientStopEffectiveData](../../com.aspose.slides/gradientstopeffectivedata)가 현재 [GradientStopEffectiveData](../../com.aspose.slides/gradientstopeffectivedata)와 같은지 확인합니다. |
| [hashCode()](#hashCode--) |  |
### getPosition() {#getPosition--}
```
public final float getPosition()
```

그라디언트 스톱의 위치(0..1)를 반환합니다. 읽기 전용 float.

**반환:**  
float
### getColor() {#getColor--}
```
public final Color getColor()
```

그라디언트 스톱의 색상을 반환합니다. 읽기 전용 java.awt.Color.

**반환:**  
java.awt.Color
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 [GradientStopEffectiveData](../../com.aspose.slides/gradientstopeffectivedata)가 현재 [GradientStopEffectiveData](../../com.aspose.slides/gradientstopeffectivedata)와 같은지 확인합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [GradientStopEffectiveData](../../com.aspose.slides/gradientstopeffectivedata). |

**반환:**  
boolean - 객체가 동일하면 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

**반환:**  
int