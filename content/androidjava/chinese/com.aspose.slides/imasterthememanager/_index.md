---
title: IMasterThemeManager
second_title: 适用于 Android 的 Aspose.Slides via Java API 参考
description: 提供对演示文稿主主题的访问。
type: docs
url: /zh/com.aspose.slides/imasterthememanager/
---
**已实现的接口：**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IMasterThemeManager extends IThemeManager
```

提供对演示文稿主主题的访问。
## 方法

| 方法 | 说明 |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | 确定 OverrideTheme 是否覆盖继承的有效主题 (Presentation.MasterTheme)。 |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | 确定 OverrideTheme 是否覆盖继承的有效主题 (Presentation.MasterTheme)。 |
| [getOverrideTheme()](#getOverrideTheme--) | 返回覆盖的主题对象。 |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | 返回覆盖的主题对象。 |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

确定 OverrideTheme 是否覆盖继承的有效主题 (Presentation.MasterTheme)。可读写 boolean。

**返回：**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public abstract void setOverrideThemeEnabled(boolean value)
```

确定 OverrideTheme 是否覆盖继承的有效主题 (Presentation.MasterTheme)。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IMasterTheme getOverrideTheme()
```

返回覆盖的主题对象。可读写 [IMasterTheme](../../com.aspose.slides/imastertheme)。

**返回：**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public abstract void setOverrideTheme(IMasterTheme value)
```

返回覆盖的主题对象。可读写 [IMasterTheme](../../com.aspose.slides/imastertheme)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |