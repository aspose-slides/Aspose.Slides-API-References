---
title: Field
second_title: Aspose.Slides for Java API 參考文件
description: 表示一個欄位。
type: docs
url: /zh-hant/com.aspose.slides/field/
---
**繼承:**  
java.lang.Object, com.aspose.slides.DomObject

**全部已實作的介面:**  
[com.aspose.slides.IField](../../com.aspose.slides/ifield)  
```
public final class Field extends DomObject<Portion> implements IField
```

表示一個欄位。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getType()](#getType--) | 返回或設定欄位的類型。 |
| [setType(IFieldType value)](#setType-com.aspose.slides.IFieldType-) | 返回或設定欄位的類型。 |
| [getSlide()](#getSlide--) | 返回段落的父投影片。 |
| [getPresentation()](#getPresentation--) | 返回段落的父簡報。 |

### getType() {#getType--}
```
public final IFieldType getType()
```

返回或設定欄位的類型。讀寫 [IFieldType](../../com.aspose.slides/ifieldtype)。

**返回值:**
[IFieldType](../../com.aspose.slides/ifieldtype)

### setType(IFieldType value) {#setType-com.aspose.slides.IFieldType-}
```
public final void setType(IFieldType value)
```

返回或設定欄位的類型。讀寫 [IFieldType](../../com.aspose.slides/ifieldtype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回段落的父投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回值:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回段落的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回值:**
[IPresentation](../../com.aspose.slides/ipresentation)