---
title: IThemeEffectiveData
second_title: Java API 참조를 통한 Aspose.Slides for Android
description: 효과적인 테마 속성을 포함하는 불변 객체입니다.
type: docs
url: /ko/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

효과적인 테마 속성을 포함하는 불변 객체입니다.

--------------------

이 인터페이스는 [ITheme](../../com.aspose.slides/itheme) 인터페이스와 함께 사용되어 상속이 적용된 효과적인 서식 값을 반환합니다.
## Methods

| 메서드 | 설명 |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | 색 구성표를 반환합니다. |
| [getFontScheme()](#getFontScheme--) | 글꼴 구성표를 반환합니다. |
| [getFormatScheme()](#getFormatScheme--) | 모양 형식 구성표를 반환합니다. |
### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```

색 구성표를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| styleColor | java.lang.Integer | 색 java.lang.Integer |

**반환값:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - 색 구성표 [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```

글꼴 구성표를 반환합니다. 읽기 전용 [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**반환값:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```

모양 형식 구성표를 반환합니다. 읽기 전용 [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**반환값:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)