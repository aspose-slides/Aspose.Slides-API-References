---
title: IBlurEffectiveData
second_title: Aspose.Slides for Android via Java API 레퍼런스
description: 채우기를 포함한 전체 모양에 적용되는 Blur 효과를 나타내는 불변 객체입니다.
type: docs
url: /ko/com.aspose.slides/iblureffectivedata/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

전체 모양과 채우기까지 적용되는 Blur 효과를 나타내는 불변 객체입니다. 알파를 포함한 모든 색상 채널이 영향을 받습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRadius()](#getRadius--) | 블러 반경을 반환하거나 설정합니다. |
| [getGrow()](#getGrow--) | 블러링 결과로 객체의 경계가 확장되어야 하는지 여부를 결정합니다. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


블러 반경을 반환하거나 설정합니다. 읽기 전용 double.

**반환:** 
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


블러링 결과로 객체의 경계가 확장되어야 하는지 여부를 결정합니다. True는 경계가 확장됨을 나타내고 false는 확장되지 않음을 나타냅니다. 읽기 전용 boolean.

**반환:** 
boolean