---
title: MasterThemeManager
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 프레젠테이션 마스터 테마에 대한 액세스를 제공합니다.
type: docs
url: /ko/com.aspose.slides/masterthememanager/
---
**상속:**  
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)  
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

프레젠테이션 마스터 테마에 대한 접근을 제공합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | 오버라이드 테마 객체를 반환합니다. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | 오버라이드 테마 객체를 반환합니다. |
| [createThemeEffective()](#createThemeEffective--) | 테마 객체를 반환합니다. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | OverrideTheme가 상속된 유효 테마 (Presentation.MasterTheme)를 오버라이드하는지 여부를 판단합니다. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | OverrideTheme가 상속된 유효 테마 (Presentation.MasterTheme)를 오버라이드하는지 여부를 판단합니다. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | 슬라이드에 추가 색 구성표를 적용합니다. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```

오버라이드 테마 객체를 반환합니다. 읽기/쓰기 [IMasterTheme](../../com.aspose.slides/imastertheme).

**반환:**  
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```

오버라이드 테마 객체를 반환합니다. 읽기/쓰기 [IMasterTheme](../../com.aspose.slides/imastertheme).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

테마 객체를 반환합니다.

**반환:**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

OverrideTheme가 상속된 유효 테마 (Presentation.MasterTheme)를 오버라이드하는지 여부를 판단합니다. 읽기/쓰기 boolean.

**반환:**  
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```

OverrideTheme가 상속된 유효 테마 (Presentation.MasterTheme)를 오버라이드하는지 여부를 판단합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

슬라이드에 추가 색 구성표를 적용합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) 객체. |