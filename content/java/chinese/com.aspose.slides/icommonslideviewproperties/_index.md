---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Java API Reference
description: Represents common slide view properties.
type: docs
url: /zh/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

表示通用幻灯片视图属性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getScale()](#getScale--) | 指定视图缩放比例（百分比）。 |
| [setScale(int value)](#setScale-int-) | 指定视图缩放比例（百分比）。 |
| [getVariableScale()](#getVariableScale--) | 指定视图内容应自动缩放以最佳适配当前窗口大小。 |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | 指定视图内容应自动缩放以最佳适配当前窗口大小。 |
| [getDrawingGuides()](#getDrawingGuides--) | 返回绘图参考线的集合。 |
### getScale() {#getScale--}
```
public abstract int getScale()
```


指定视图缩放比例（百分比）。读/写 int.

**返回：**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


指定视图缩放比例（百分比）。读/写 int.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```


指定视图内容应自动缩放以最佳适配当前窗口大小。读/写 boolean.

**返回：**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```


指定视图内容应自动缩放以最佳适配当前窗口大小。读/写 boolean.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


返回绘图参考线的集合。只读 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // 在幻灯片中心右侧添加新的垂直绘图参考线
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // 在幻灯片中心下方添加新的水平绘图参考线
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回：**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)