---
title: HyperlinkManager
second_title: Aspose.Slides Java API 参考
description: 提供超链接的添加与删除管理。
type: docs
url: /zh/com.aspose.slides/hyperlinkmanager/
---
**继承：**
java.lang.Object

**已实现的接口：**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

提供超链接管理（添加，删除）。
## 方法

| 方法 | 描述 |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | 设置点击时的外部超链接。 |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | 设置点击时的内部超链接。 |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | 点击时移除超链接。 |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | 设置外部超链接鼠标悬停。 |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | 设置内部超链接鼠标悬停。 |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | 移除鼠标悬停超链接。 |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | 在点击时设置宏超链接。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

设置点击时的外部超链接。

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // 实例化表示 PPTX 的 Presentation 类
>  Presentation pres = new Presentation();
>  try {
>      // 获取演示文稿中的第一张幻灯片
>      ISlide slide = pres.getSlides().get_Item(0);
>      // 添加一个类型为矩形的 AutoShape 对象
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // 将形状强制转换为 AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // 访问与 AutoShape 关联的 ITextFrame 属性
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // 向框中添加一些文本
>      portion.setText("Aspose.Slides");
>      // 为片段文本设置超链接
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // 保存 PPTX 演示文稿
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | java.lang.String | 超链接 URL。 |

**返回值：**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

设置点击时的内部超链接。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 目标幻灯片。 |

**返回值：**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```

点击时移除超链接。

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```

设置外部超链接鼠标悬停。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | java.lang.String | 超链接 URL。 |

**返回值：**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

设置内部超链接鼠标悬停。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 目标幻灯片。 |

**返回值：**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```

移除鼠标悬停超链接。

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```

点击时设置宏超链接。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| macroName | java.lang.String | 宏的名称 |

**返回值：**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回值：**
com.aspose.slides.IDOMObject