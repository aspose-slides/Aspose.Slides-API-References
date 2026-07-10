---
title: IOverrideThemeManager
second_title: Aspose.Slides for Android via Java API 参考
description: 提供对不同类型已覆盖主题的访问。
type: docs
url: /zh/com.aspose.slides/ioverridethememanager/
---
**所有实现的接口:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

提供对不同类型的已覆盖主题的访问。
## 方法

| 方法 | 描述 |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | 确定 OverrideTheme 是否覆盖继承的有效主题。 |
| [getOverrideTheme()](#getOverrideTheme--) | 返回覆盖的主题对象。 |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | 返回覆盖的主题对象。 |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

确定 OverrideTheme 是否覆盖继承的有效主题。要进行覆盖，请使用 OverrideTheme.Init*() 方法。要禁用 OverrideTheme 的覆盖，请使用 OverrideTheme.Clear() 方法。只读 boolean。

**返回:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

返回覆盖的主题对象。读/写 [IOverrideTheme](../../com.aspose.slides/ioverridetheme)。

**返回:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

返回覆盖的主题对象。读/写 [IOverrideTheme](../../com.aspose.slides/ioverridetheme)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |