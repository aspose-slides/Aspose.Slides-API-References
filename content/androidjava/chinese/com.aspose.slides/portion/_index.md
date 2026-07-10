---
title: Portion
second_title: Aspose.Slides Android 通过 Java API 参考
description: 表示文本段落中的一段文本。
type: docs
url: /zh/com.aspose.slides/portion/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

表示文本段落中的一段文本。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Portion()](#Portion--) | 初始化 Portion 类的新实例。 |
| [Portion(String str)](#Portion-java.lang.String-) | 初始化 Portion 类的新实例。 |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | 初始化 Portion 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | 返回格式化对象，该对象包含未应用继承的文本片段的显式设置的格式属性。 |
| [getText()](#getText--) | 获取或设置 portion 的纯文本。 |
| [setText(String value)](#setText-java.lang.String-) | 获取或设置 portion 的纯文本。 |
| [getField()](#getField--) | 返回此 portion 的字段。 |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | 将此 portion 转换为自动更新的字段。 |
| [addField(String internalString)](#addField-java.lang.String-) | 将此 portion 转换为自动更新的字段。 |
| [removeField()](#removeField--) | 将此字段 portion 转换为普通 portion。 |
| [getRect()](#getRect--) | 获取包围 portion 的 rect 的坐标。 |
| [getCoordinates()](#getCoordinates--) | 获取 portion 起始位置的坐标。 |
| [getSlide()](#getSlide--) | 返回文本所属的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回文本所属的父演示文稿。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Portion() {#Portion--}
```
public Portion()
```

初始化 Portion 类的新实例。

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

初始化 Portion 类的新实例。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

初始化 Portion 类的新实例。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

返回格式化对象，该对象包含未应用继承的文本片段的显式设置的格式属性。只读 [IPortionFormat](../../com.aspose.slides/iportionformat)。

--------------------

格式对象仅包含为当前 portion 定义的格式参数，不会应用继承的数据。

为了获取包括继承在内的有效值，请使用 [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) 方法。

**返回：**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getText() {#getText--}
```
public final String getText()
```

获取或设置 portion 的纯文本。读/写 String。

值：文本。

**返回：**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

获取或设置 portion 的纯文本。读/写 String。

值：文本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

返回此 portion 的字段。只读 [IField](../../com.aspose.slides/ifield)。

**返回：**
[IField](../../com.aspose.slides/ifield)

### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

将此 portion 转换为自动更新的字段。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

将此 portion 转换为自动更新的字段。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| internalString | java.lang.String | 字段类型的内部名称。 |

### removeField() {#removeField--}
```
public final void removeField()
```

将此字段 portion 转换为普通 portion。

### getRect() {#getRect--}
```
public final RectF getRect()
```

获取包围 portion 的 rect 的坐标。该 rect 包含 portion 中的所有文本行，包括空行。

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
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public final PointF getCoordinates()
```


Get coordinates of the beginning of the portion. The X coordinate of point represents the portion beginning from the first character including left side bearing. The Y coordinate includes top side bearing.

**Returns:**
android.graphics.PointF
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回文本的父幻灯片。只读 [BaseSlide](../../com.aspose.slides/baseslide).

**返回：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回文本的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation).

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()


返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject