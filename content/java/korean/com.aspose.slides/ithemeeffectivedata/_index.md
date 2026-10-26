---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective theme properties.
type: docs
url: /ko/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

효과적인 테마 속성을 포함하는 불변 객체입니다.

--------------------

이 인터페이스는 [ITheme](../../com.aspose.slides/itheme) 인터페이스와 함께 사용되어 상속이 적용된 효과적인 서식 값을 반환합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | 색 구성표를 반환합니다. |
| [getFontScheme()](#getFontScheme--) | 폰트 구성표를 반환합니다. |
| [getFormatScheme()](#getFormatScheme--) | 도형 서식 구성표를 반환합니다. |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```


색 구성표를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**반환:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - Color scheme [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```


폰트 구성표를 반환합니다. 읽기 전용 [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**반환:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```


도형 서식 구성표를 반환합니다. 읽기 전용 [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**반환:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)