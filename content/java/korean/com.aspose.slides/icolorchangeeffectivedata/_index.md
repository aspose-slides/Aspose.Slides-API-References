---
title: IColorChangeEffectiveData
second_title: Aspose.Slides for Java API 참조
description: Color Change 효과를 나타내는 불변 객체.
type: docs
url: /ko/com.aspose.slides/icolorchangeeffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorChangeEffectiveData extends IEffectEffectiveData
```

불변 객체이며 Color Change 효과를 나타냅니다. FromColor 인스턴스는 ToColor 인스턴스로 교체됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFromColor()](#getFromColor--) | 교체될 Color. |
| [getToColor()](#getToColor--) | 대체할 Color. |
| [getUseAlpha()](#getUseAlpha--) | 알파 구성 요소를 사용할지 여부를 결정하는 boolean 값을 반환합니다. |
### getFromColor() {#getFromColor--}
```
public abstract Color getFromColor()
```

교체될 Color. 읽기 전용 java.awt.Color.

**반환값:**
java.awt.Color
### getToColor() {#getToColor--}
```
public abstract Color getToColor()
```

대체할 Color. 읽기 전용 java.awt.Color.

**반환값:**
java.awt.Color
### getUseAlpha() {#getUseAlpha--}
```
public abstract boolean getUseAlpha()
```

알파 구성 요소를 사용할지 여부를 결정하는 boolean 값을 반환합니다. 읽기 전용 boolean.

**반환값:**
boolean