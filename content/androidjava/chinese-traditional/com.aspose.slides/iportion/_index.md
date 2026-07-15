---
title: IPortion
second_title: Aspose.Slides for Android via Java API 參考
description: 表示文字段落內的一段文字。
type: docs
url: /zh-hant/com.aspose.slides/iportion/
---
**已實作的所有介面：**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

表示文字段落內的一段文字。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | 返回格式化對象，該對象包含明確設定的文字段落部分的格式屬性，且未套用任何繼承。 |
| [getText()](#getText--) | 取得或設定該段的純文字。 |
| [setText(String value)](#setText-java.lang.String-) | 取得或設定該段的純文字。 |
| [getField()](#getField--) | 返回此段的欄位。 |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | 將此段轉換為自動更新的欄位。 |
| [addField(String internalString)](#addField-java.lang.String-) | 將此段轉換為自動更新的欄位。 |
| [removeField()](#removeField--) | 將此欄位段轉換為簡單段落。 |
| [getRect()](#getRect--) | 取得界定該段的矩形座標。 |
| [getCoordinates()](#getCoordinates--) | 取得該段起始位置的座標。 |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

返回格式化對象，該對象包含明確設定的文字段落部分的格式屬性，且未套用任何繼承。唯讀 [IPortionFormat](../../com.aspose.slides/iportionformat)。

--------------------

此格式化對象僅包含當前段定義的格式參數，未套用繼承的資料。

若要取得包含繼承在內的有效值，請使用 [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) 方法。

**傳回值：**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```

取得或設定該段的純文字。可讀寫 String。

值：文字。

**傳回值：**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

取得或設定該段的純文字。可讀寫 String。

值：文字。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public abstract IField getField()
```

返回此段的欄位。唯讀 [IField](../../com.aspose.slides/ifield)。

**傳回值：**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```

將此段轉換為自動更新的欄位。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | 欄位類型 [IFieldType](../../com.aspose.slides/ifieldtype) |

### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```

將此段轉換為自動更新的欄位。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| internalString | java.lang.String | FieldTypeEx String 的內部名稱 |

### removeField() {#removeField--}
```
public abstract void removeField()
```

將此欄位段轉換為簡單段落。

### getRect() {#getRect--}
```
public abstract RectF getRect()
```

取得界定該段的矩形座標。該矩形包含段落中所有文字行，包括空行。

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
android.graphics.RectF - 界定該段的矩形 android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public abstract PointF getCoordinates()
```

取得該段起始位置的座標。點的 X 座標表示從第一個字元起算的段起始位置（包含左側留白）。Y 座標包含上側留白。

**傳回值：**
android.graphics.PointF - 該段起始位置的座標 android.graphics.PointF