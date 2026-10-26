---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides for Android via Java API 参考
description: 表示管理器，该管理器保存所有幻灯片类型的页脚、日期时间和页码占位符的行为。
type: docs
url: /zh/com.aspose.slides/ibaseslideheaderfootermanager/
---
**所有已实现的接口:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

表示管理器，该管理器保存所有幻灯片类型的页脚、日期时间、页码占位符的行为。
## 方法

| 方法 | 描述 |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | 获取指示页脚占位符是否存在的值。 |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | 获取指示页码占位符是否存在的值。 |
| [isDateTimeVisible()](#isDateTimeVisible--) | 获取指示日期时间占位符是否存在的值。 |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | 更改幻灯片页脚占位符的可见性。 |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | 更改幻灯片页码占位符的可见性。 |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | 更改幻灯片日期时间占位符的可见性。 |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | 设置幻灯片页脚占位符的文本。 |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | 设置幻灯片日期时间占位符的文本。 |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

获取指示页脚占位符是否存在的值。读取布尔值。

**返回值:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

获取指示页码占位符是否存在的值。读取布尔值。

**返回值:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

获取指示日期时间占位符是否存在的值。读取布尔值。

**返回值:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

更改幻灯片页脚占位符的可见性。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使页脚占位符可见，否则 - 隐藏它。 |
### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

更改幻灯片页码占位符的可见性。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使页码占位符可见，否则 - 隐藏它。 |
### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

更改幻灯片日期时间占位符的可见性。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使日期时间占位符可见，否则 - 隐藏它。 |
### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

设置幻灯片页脚占位符的文本。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |
### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

设置幻灯片日期时间占位符的文本。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |