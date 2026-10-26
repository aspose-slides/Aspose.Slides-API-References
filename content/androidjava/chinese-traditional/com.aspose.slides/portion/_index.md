---
title: Portion
second_title: Aspose.Slides for Android via Java API 參考
description: 表示文字段落內的一段文字。
type: docs
url: /zh-hant/com.aspose.slides/portion/
---
**繼承：**
java.lang.Object

**所有已實作介面：**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

表示文字段落內的一段文字。
## 建構式

| 建構式 | 說明 |
| --- | --- |
| [Portion()](#Portion--) | 初始化 Portion 類別的新執行個體。 |
| [Portion(String str)](#Portion-java.lang.String-) | 初始化 Portion 類別的新執行個體。 |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | 初始化 Portion 類別的新執行個體。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | 傳回格式物件，其中包含未套用繼承的文字段落明確設定的格式屬性。 |
| [getText()](#getText--) | 取得或設定此段落的純文字。 |
| [setText(String value)](#setText-java.lang.String-) | 取得或設定此段落的純文字。 |
| [getField()](#getField--) | 傳回此段落的欄位。 |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | 將此段落轉換為自動更新的欄位。 |
| [addField(String internalString)](#addField-java.lang.String-) | 将此段落轉換為自動更新的欄位。 |
| [removeField()](#removeField--) | 將此欄位段落轉換為普通段落。 |
| [getRect()](#getRect--) | 取得界定此段落的矩形座標。 |
| [getCoordinates()](#getCoordinates--) | 取得此段落起始點的座標。 |
| [getSlide()](#getSlide--) | 傳回文字的上層投影片。 |
| [getPresentation()](#getPresentation--) | 傳回文字的上層簡報。 |
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

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```


初始化 Portion 類別的新執行個體。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```


傳回格式物件，其中包含未套用繼承的文字段落明確設定的格式屬性。唯讀 [IPortionFormat](../../com.aspose.slides/iportionformat)。

--------------------

格式物件僅包含目前段落定義的格式參數，未套用繼承的資料。

若需取得包含繼承值的實際值，請使用 [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) 方法。

**傳回值：**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```


取得或設定此段落的純文字。可讀寫 String。

值：文字。

**傳回值：**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


取得或設定此段落的純文字。可讀寫 String。

值：文字。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```


傳回此段落的欄位。唯讀 [IField](../../com.aspose.slides/ifield)。

**傳回值：**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```


將此段落轉換為自動更新的欄位。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```


將此段落轉換為自動更新的欄位。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| internalString | java.lang.String | FieldType 的內部名稱。 |

### removeField() {#removeField--}
```
public final void removeField()
```


將此欄位段落轉換為普通段落。

### getRect() {#getRect--}
```
public final RectF getRect()
```


取得界定此段落的矩形座標。該矩形包含段落中所有文字行，包括空行。

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


**傳回值：**
android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public final PointF getCoordinates()
```


取得此段落起始點的座標。點的 X 座標表示從首字符左側邊距開始的段落起始位置，Y 座標包含頂部邊距。

**傳回值：**
android.graphics.PointF
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


傳回文字的上層投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**傳回值：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


傳回文字的上層簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**傳回值：**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回值：**
com.aspose.slides.IDOMObject