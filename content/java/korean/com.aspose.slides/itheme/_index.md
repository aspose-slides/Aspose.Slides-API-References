---
title: ITheme
second_title: Aspose.Slides for Java API 참조
description: 테마를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/itheme/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

테마를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | 색 구성표를 반환합니다. |
| [getFontScheme()](#getFontScheme--) | 글꼴 구성표를 반환합니다. |
| [getFormatScheme()](#getFormatScheme--) | 도형 형식 구성표를 반환합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 실제 테마 데이터를 가져옵니다. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


색 구성표를 반환합니다. 읽기 전용 [IColorScheme](../../com.aspose.slides/icolorscheme).

**반환:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


글꼴 구성표를 반환합니다. 읽기 전용 [IFontScheme](../../com.aspose.slides/ifontscheme).

**반환:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


도형 형식 구성표를 반환합니다. 읽기 전용 [IFormatScheme](../../com.aspose.slides/iformatscheme).

**반환:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


상속이 적용된 실제 테마 데이터를 가져옵니다.

**반환:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).