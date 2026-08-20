---
title: Portion
second_title: Aspose.Slides for Java API 參考文件
description: 表示文字段落內的文字片段。
type: docs
url: /zh-hant/com.aspose.slides/portion/
---
**繼承:**  
java.lang.Object

**所有已實作的介面:**  
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject  
```
public class Portion implements IPortion, IDOMObject
```

表示文字段落內的文字片段。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [Portion()](#Portion--) | 初始化 Portion 類別的新執行個體。 |
| [Portion(String str)](#Portion-java.lang.String-) | 初始化 Portion 類別的新執行個體。 |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | 初始化 Portion 類別的新執行個體。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | 傳回格式化物件，包含未套用繼承的文字 Portion 的明確設定格式屬性。 |
| [getText()](#getText--) | 取得或設定 Portion 的純文字。 |
| [setText(String value)](#setText-java.lang.String-) | 取得或設定 Portion 的純文字。 |
| [getField()](#getField--) | 傳回此 Portion 的欄位。 |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | 將此 Portion 轉換為自動更新的欄位。 |
| [addField(String internalString)](#addField-java.lang.String-) | 將此 Portion 轉換為自動更新的欄位。 |
| [removeField()](#removeField--) | 將此欄位 Portion 轉換為簡易 Portion。 |
| [getRect()](#getRect--) | 取得包圍 Portion 的矩形座標。 |
| [getCoordinates()](#getCoordinates--) | 取得 Portion 起始位置的座標。 |
| [getSlide()](#getSlide--) | 傳回文字的父投影片。 |
| [getPresentation()](#getPresentation--) | 傳回文字的父簡報。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Portion() {#Portion--}
```
public Portion()
```

初始化 Portion 類別的新執行個體。

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

初始化 Portion 類別的新執行個體。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

初始化 Portion 類別的新執行個體。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

傳回格式化物件，包含未套用繼承的文字 Portion 的明確設定格式屬性。唯讀 [IPortionFormat](../../com.aspose.slides/iportionformat)。

--------------------

此格式化物件僅包含為當前 Portion 定義的格式參數，未套用繼承的資料。

若要取得包括繼承值在內的有效值，請使用 [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) 方法。

**傳回值:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getText() {#getText--}
```
public final String getText()
```

取得或設定 Portion 的純文字。可讀寫 String。

值：文字。

**傳回值:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

取得或設定 Portion 的純文字。可讀寫 String。

值：文字。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

傳回此 Portion 的欄位。唯讀 [IField](../../com.aspose.slides/ifield)。

**傳回值:**
[IField](../../com.aspose.slides/ifield)

### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

將此 Portion 轉換為自動更新的欄位。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

將此 Portion 轉換為自動更新的欄位。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| internalString | java.lang.String | FieldType 的內部名稱。 |

### removeField() {#removeField--}
```
public final void removeField()
```

將此欄位 Portion 轉換為簡易 Portion。

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

取得包圍 Portion 的矩形座標。該矩形包括 Portion 中的所有文字行，亦包括空行。

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


**傳回值:**
java.awt.geom.Rectangle2D.Float

### getCoordinates() {#getCoordinates--}
```
public final Point2D.Float getCoordinates()
```

取得 Portion 起始位置的座標。點的 X 座標代表從第一個字元起算的 Portion 起點（包括左側留白）。Y 座標包括上側留白。

**傳回值:**
java.awt.geom.Point2D.Float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

傳回文字的父投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**傳回值:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

傳回文字的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**傳回值:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回值:**
com.aspose.slides.IDOMObject