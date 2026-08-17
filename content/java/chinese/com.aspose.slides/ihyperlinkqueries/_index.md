---
title: IHyperlinkQueries
second_title: Aspose.Slides for Java API Reference
description: 提供对包含的超链接的便捷访问。
type: docs
url: /zh/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

提供对包含的超链接的便捷访问。
## 方法

| Method | Description |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | 获取所有 IHyperlinkContainer 子对象，其中包含非空 HyperlinkClick。 |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | 获取所有 IHyperlinkContainer 子对象，其中包含非空 HyperlinkMouseOver。 |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | 获取所有 IHyperlinkContainer 子对象，其中包含非空 HyperlinkMouseOver。 |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | 删除所有包含的 HyperlinkClick 和 HyperlinkMouseOver 超链接（在所有 IHyperlinkContainer 子对象中）。 |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```


获取所有 IHyperlinkContainer 子对象，其中包含非空 HyperlinkClick。使用给定的 IHyperlinkContainer 对象，您可以管理其超链接（读取、更新或删除）。参见 IHyperlinkContainer 接口。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - 所有 IHyperlinkContainer 子对象，其中包含非空 HyperlinkClick
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```


获取所有 IHyperlinkContainer 子对象，其中包含非空 HyperlinkMouseOver。使用给定的 IHyperlinkContainer 对象，您可以管理其超链接（读取、更新或删除）。参见 IHyperlinkContainer 接口。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - 所有 IHyperlinkContainer 子对象，其中包含非空 HyperlinkMouseOver
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```


获取所有 IHyperlinkContainer 子对象，其中包含非空 HyperlinkMouseOver。使用给定的 IHyperlinkContainer 对象，您可以管理其超链接（读取、更新或删除）。参见 IHyperlinkContainer 接口。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - 所有 IHyperlinkContainer 子对象，其中包含非空 HyperlinkMouseOver
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```


删除所有包含的 HyperlinkClick 和 HyperlinkMouseOver 超链接（在所有 IHyperlinkContainer 子对象中）。