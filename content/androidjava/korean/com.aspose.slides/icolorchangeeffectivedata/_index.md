---
title: IColorChangeEffectiveData
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 색상 변경 효과를 나타내는 불변 객체입니다.
type: docs
url: /ko/com.aspose.slides/icolorchangeeffectivedata/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorChangeEffectiveData extends IEffectEffectiveData
```

색상 변경 효과를 나타내는 불변 객체입니다. FromColor 인스턴스는 ToColor 인스턴스로 대체됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFromColor()](#getFromColor--) | 대체될 색상. |
| [getToColor()](#getToColor--) | 대체할 색상. |
| [getUseAlpha()](#getUseAlpha--) | 알파 구성 요소를 사용할지 여부를 결정하는 부울 값을 반환합니다. |
### getFromColor() {#getFromColor--}
```
public abstract Integer getFromColor()
```


대체될 색상. 읽기 전용 java.lang.Integer.

**반환:**  
java.lang.Integer
### getToColor() {#getToColor--}
```
public abstract Integer getToColor()
```


대체할 색상. 읽기 전용 java.lang.Integer.

**반환:**  
java.lang.Integer
### getUseAlpha() {#getUseAlpha--}
```
public abstract boolean getUseAlpha()
```


알파 구성 요소를 사용할지 여부를 결정하는 부울 값을 반환합니다. 읽기 전용 boolean.

**반환:**  
boolean