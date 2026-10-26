---
title: IOverrideThemeManager
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 다양한 유형의 재정의된 테마에 대한 액세스를 제공합니다.
type: docs
url: /ko/com.aspose.slides/ioverridethememanager/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

다양한 유형의 재정의된 테마에 대한 액세스를 제공합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | OverrideTheme가 상속된 유효 테마를 재정의하는지 여부를 결정합니다. |
| [getOverrideTheme()](#getOverrideTheme--) | 재정의된 테마 개체를 반환합니다. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | 재정의된 테마 개체를 반환합니다. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

OverrideTheme가 상속된 유효 테마를 재정의하는지 여부를 결정합니다. OverrideTheme를 재정의하도록 활성화하려면 OverrideTheme.Init\*() 메서드를 사용합니다. OverrideTheme가 재정의를 하지 않도록 비활성화하려면 OverrideTheme.Clear() 메서드를 사용합니다. 읽기 전용 boolean.

**반환:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

재정의된 테마 개체를 반환합니다. 읽기/쓰기 [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**반환:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

재정의된 테마 개체를 반환합니다. 읽기/쓰기 [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |