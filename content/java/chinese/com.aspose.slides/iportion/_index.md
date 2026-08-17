---
title: IPortion
second_title: Aspose.Slides Java API 参考
description: 表示文本段落内部的一段文本。
type: docs
url: /zh/com.aspose.slides/iportion/
---
**所有实现的接口：**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

表示文本段落内的一段文本。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | 返回格式化对象，该对象包含对文本段落部分明确设置的格式属性，且不应用继承。 |
| [getText()](#getText--) | 获取或设置该部分的纯文本。 |
| [setText(String value)](#setText-java.lang.String-) | 获取或设置该部分的纯文本。 |
| [getField()](#getField--) | 返回此部分的字段。 |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | 将此部分转换为自动更新的字段。 |
| [addField(String internalString)](#addField-java.lang.String-) | 将此部分转换为自动更新的字段。 |
| [removeField()](#removeField--) | 将此字段部分转换为普通部分。 |
| [getRect()](#getRect--) | 获取包围该部分的矩形坐标。 |
| [getCoordinates()](#getCoordinates--) | 获取该部分起始位置的坐标。 |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```


返回格式化对象，该对象包含对文本段落部分明确设置的格式属性，且不应用继承。只读 [IPortionFormat](../../com.aspose.slides/iportionformat)。

--------------------

此格式化对象仅包含当前部分定义的格式参数，不应用继承的数据。

若要获取包括继承值在内的有效值，请使用 [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) 方法。

**返回：**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```


获取或设置该部分的纯文本。读/写 String。

值：文本。

**返回：**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


获取或设置该部分的纯文本。读/写 String。

值：文本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public abstract IField getField()
```


返回此部分的字段。只读 [IField](../../com.aspose.slides/ifield)。

**返回：**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```


将此部分转换为自动更新的字段。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | 字段的类型 [IFieldType](../../com.aspose.slides/ifieldtype) |

### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```


将此部分转换为自动更新的字段。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| internalString | java.lang.String | FieldTypeEx String 的内部名称 |

### removeField() {#removeField--}
```
public abstract void removeField()
```


将此字段部分转换为普通部分。

### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```


获取包围该部分的矩形坐标。该矩形包含该部分的所有文本行，包括空行。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try
>  {
>  	ISlide slide = pres.getSlides().get_Item(0);
>  	IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 200, 50);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().clear();
>  	Portion portion0 = new Portion("Some text");
>  	Portion portion1 = new Portion("GetRect text");
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion0);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion1);
>  	Rectangle2D.Float rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**返回：**
java.awt.geom.Rectangle2D.Float - 包围该部分的矩形 java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public abstract Point2D.Float getCoordinates()
```


获取该部分起始位置的坐标。点的 X 坐标表示从第一个字符（包括左侧留白）开始的部分起始位置。Y 坐标包括顶部留白。

**返回：**
java.awt.geom.Point2D.Float - 该部分起始位置的坐标 java.awt.geom.Point2D.Float