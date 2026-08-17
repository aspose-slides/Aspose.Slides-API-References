---
title: PortionFormat
second_title: Aspose.Slides for Java API 参考
description: 此类包含文本部分的格式属性。
type: docs
url: /zh/com.aspose.slides/portionformat/
---
**继承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**所有实现的接口:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

此类包含文本部分的格式属性。不同于[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)，此类的所有属性均可写。

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //实例化一个表示演示文件的 Presentation 对象
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides 使用这些特殊标识符（类似于 PowerPoint 中使用的标识符）：
>      // +mn-lt - 正文字体 拉丁文（次要拉丁字体）
>      // +mj-lt - 标题字体 拉丁文（主要拉丁字体）
>      // +mn-ea - 正文字体 东亚文字（次要东亚字体）
>      // +mj-ea - 正文字体 东亚文字（次要东亚字体）
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

此类用于返回和操作为特定部分定义的文本部分格式属性。这意味着在获取值时不应用继承，因此在大多数情况下您将获得表示“未定义”的值。

为了获取包括继承在内的有效格式参数值，您需要使用[getEffective](../../com.aspose.slides/portionformat\#getEffective)方法，该方法返回一个[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)实例。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | 初始化 [PortionFormat](../../com.aspose.slides/portionformat) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | 返回或设置书签标识符。 |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | 返回或设置书签标识符。 |
| [getSmartTagClean()](#getSmartTagClean--) | 确定是否应清除智能标签。 |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | 确定是否应清除智能标签。 |
| [getHyperlinkClick()](#getHyperlinkClick--) | 返回或设置鼠标点击定义的超链接。 |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | 返回或设置鼠标点击定义的超链接。 |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | 返回或设置鼠标悬停定义的超链接。 |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | 返回或设置鼠标悬停定义的超链接。 |
| [getHyperlinkManager()](#getHyperlinkManager--) | 超链接管理器。 |
| [getEffective()](#getEffective--) | 获取应用继承后的有效部分格式数据。 |
### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```


初始化 [PortionFormat](../../com.aspose.slides/portionformat) 类的新实例。

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```


返回或设置书签标识符。读取/写入 String。

**返回:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```


返回或设置书签标识符。读取/写入 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```


确定是否应清除智能标签。未应用继承。读取/写入 boolean 。

**返回:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```


确定是否应清除智能标签。未应用继承。读取/写入 boolean 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```


返回或设置鼠标点击定义的超链接。读取/写入 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**返回:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```


返回或设置鼠标点击定义的超链接。读取/写入 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```


返回或设置鼠标悬停定义的超链接。读取/写入 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**返回:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```


返回或设置鼠标悬停定义的超链接。读取/写入 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```


超链接管理器。只读 [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)。

**返回:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```


获取应用继承后的有效部分格式数据。

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**返回:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - 一个 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).