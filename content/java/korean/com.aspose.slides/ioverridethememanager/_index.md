---
title: IOverrideThemeManager
second_title: Java API 참조용 Aspose.Slides
description: 오버라이드된 테마의 다양한 유형에 대한 액세스를 제공합니다.
type: docs
url: /ko/com.aspose.slides/ioverridethememanager/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

오버라이드된 테마의 다양한 유형에 대한 액세스를 제공합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | OverrideTheme가 상속된 유효 테마를 오버라이드하는지 여부를 판단합니다. |
| [getOverrideTheme()](#getOverrideTheme--) | 오버라이드된 테마 객체를 반환합니다. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | 오버라이드된 테마 객체를 반환합니다. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```


OverrideTheme가 상속된 유효 테마를 오버라이드하는지 여부를 판단합니다. OverrideTheme를 오버라이드하도록 사용하려면 OverrideTheme.Init\*() 메서드를 사용하십시오. OverrideTheme가 오버라이드되지 않도록 하려면 OverrideTheme.Clear() 메서드를 사용하십시오. 읽기 전용 boolean.

**반환:**  
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```


오버라이드된 테마 객체를 반환합니다. 읽기/쓰기 [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**반환:**  
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```


오버라이드된 테마 객체를 반환합니다. 읽기/쓰기 [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |