---
title: BaseOverrideThemeManager
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 다양한 유형의 재정의된 테마에 대한 액세스를 제공하는 클래스의 기본 클래스입니다.
type: docs
url: /ko/com.aspose.slides/baseoverridethememanager/
---
**상속:**  
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)  
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

다양한 종류의 재정의된 테마에 대한 액세스를 제공하는 클래스의 기본 클래스입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | 재정의된 테마 객체를 반환합니다. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | 재정의된 테마 객체를 반환합니다. |
| [createThemeEffective()](#createThemeEffective--) | 테마 객체를 반환합니다. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | OverrideTheme가 상속된 효과 테마를 재정의하는지 여부를 결정합니다. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | 슬라이드에 추가 색 구성표를 적용합니다. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

재정의된 테마 객체를 반환합니다. 읽기/쓰기 [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**반환:**  
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

재정의된 테마 객체를 반환합니다. 읽기/쓰기 [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

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

OverrideTheme가 상속된 효과 테마를 재정의하는지 여부를 결정합니다. OverrideTheme를 재정의하려면 OverrideTheme.Init\*() 메서드를 사용하십시오. OverrideTheme의 재정을 해제하려면 OverrideTheme.Clear() 메서드를 사용하십시오. 읽기 전용 boolean.

**반환:**  
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

슬라이드에 추가 색 구성표를 적용합니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) 객체. |