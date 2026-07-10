---
title: HyperlinkManager
second_title: Aspose.Slides for Android Java API 参考
description: 提供超链接的添加和删除管理。
type: docs
url: /zh/com.aspose.slides/hyperlinkmanager/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

提供超链接管理（添加、删除）。
## 方法

| 方法 | 描述 |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | 在点击时设置外部超链接。 |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | 在点击时设置内部超链接。 |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | 在点击时移除超链接。 |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | 在鼠标悬停时设置外部超链接。 |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | 在鼠标悬停时设置内部超链接。 |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | 在鼠标悬停时移除超链接。 |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | 在点击时设置宏超链接。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

在点击时设置外部超链接。

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // 实例化一个表示 PPTX 的 Presentation 类
>  Presentation pres = new Presentation();
>  try {
>      // 获取演示文稿中的第一张幻灯片
>      ISlide slide = pres.getSlides().get_Item(0);
>      // 添加一个类型为 Rectangle 的 AutoShape 对象
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // 将形状强制转换为 AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // 访问与 AutoShape 关联的 ITextFrame 属性
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // 向框中添加一些文本
>      portion.setText("Aspose.Slides");
>      // 为该段文字设置超链接
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // 保存 PPTX 演示文稿
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | Hyperlink URL. |

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Sets internal hyperlink on click.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Target slide. |

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```

 

Removes hyperlink on click.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```

Sets external hyperlink mouse over.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | Hyperlink URL. |

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Sets internal hyperlink mouse over.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Target slide. |

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```

Removes hyperlink mouse over.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```
Set Macro hyperlink on a click.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.BlankButton, 20, 20, 80, 30);
>      shape.getHyperlinkManager().setMacroHyperlinkClick("MacroName");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| macroName | java.lang.String | Name of the macro |

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject
