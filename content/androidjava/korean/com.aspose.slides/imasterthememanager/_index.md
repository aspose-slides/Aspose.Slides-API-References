---
title: IMasterThemeManager
second_title: Java API 레퍼런스를 통해 Android용 Aspose.Slides
description: 프레젠테이션 마스터 테마에 대한 액세스를 제공합니다.
type: docs
url: /ko/com.aspose.slides/imasterthememanager/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IMasterThemeManager extends IThemeManager
```

프레젠테이션 마스터 테마에 대한 액세스를 제공합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | OverrideTheme가 상속된 실제 테마 (Presentation.MasterTheme)를 재정의하는지 여부를 결정합니다. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | OverrideTheme가 상속된 실제 테마 (Presentation.MasterTheme)를 재정의하는지 여부를 결정합니다. |
| [getOverrideTheme()](#getOverrideTheme--) | 재정의된 테마 객체를 반환합니다. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | 재정의된 테마 객체를 반환합니다. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

OverrideTheme가 상속된 실제 테마 (Presentation.MasterTheme)를 재정의하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public abstract void setOverrideThemeEnabled(boolean value)
```

OverrideTheme가 상속된 실제 테마 (Presentation.MasterTheme)를 재정의하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IMasterTheme getOverrideTheme()
```

재정의된 테마 객체를 반환합니다. 읽기/쓰기 [IMasterTheme](../../com.aspose.slides/imastertheme).

**반환값:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public abstract void setOverrideTheme(IMasterTheme value)
```

재정의된 테마 객체를 반환합니다. 읽기/쓰기 [IMasterTheme](../../com.aspose.slides/imastertheme).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |