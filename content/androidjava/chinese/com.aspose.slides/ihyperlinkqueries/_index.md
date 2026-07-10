---
title: IHyperlinkQueries
second_title: Aspose.Slides for Android via Java API Reference
description: 提供对包含的超链接的便捷访问。
type: docs
url: /zh/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

提供对包含的超链接的便捷访问。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | 获取所有包含非空 HyperlinkClick 的 IHyperlinkContainer 子对象。 |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | 获取所有包含非空 HyperlinkMouseOver 的 IHyperlinkContainer 子对象。 |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | 获取所有包含非空 HyperlinkMouseOver 的 IHyperlinkContainer 子对象。 |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | 移除所有包含的 HyperlinkClick 和 HyperlinkMouseOver 超链接（在所有 IHyperlinkContainer 子对象中）。 |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

获取所有包含非空 HyperlinkClick 的 IHyperlinkContainer 子对象。使用给定的 IHyperlinkContainer 对象可以管理其超链接（读取、更新或删除）。参见 IHyperlinkContainer 接口。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkClick
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

获取所有包含非空 HyperlinkMouseOver 的 IHyperlinkContainer 子对象。使用给定的 IHyperlinkContainer 对象可以管理其超链接（读取、更新或删除）。参见 IHyperlinkContainer 接口。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

获取所有包含非空 HyperlinkMouseOver 的 IHyperlinkContainer 子对象。使用给定的 IHyperlinkContainer 对象可以管理其超链接（读取、更新或删除）。参见 IHyperlinkContainer 接口。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

移除所有包含的 HyperlinkClick 和 HyperlinkMouseOver 超链接（在所有 IHyperlinkContainer 子对象中）。