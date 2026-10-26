---
title: Format
second_title: Aspose.Slides for Android via Java API 參考
description: 代表圖表格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/format/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**  
[com.aspose.slides.IFormat](../../com.aspose.slides/iformat)  
```
public final class Format extends PVIObject implements IFormat
```

代表圖表格式屬性。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFill()](#getFill--) | 傳回圖表的填充樣式屬性。 |
| [getLine()](#getLine--) | 傳回圖表的線條樣式屬性。 |
| [getEffect()](#getEffect--) | 傳回圖表使用的效果。 |
| [getEffect3D()](#getEffect3D--) | 傳回圖表的 3D 格式。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long.

**傳回:**  
long

### getFill() {#getFill--}
```
public final IFillFormat getFill()
```

傳回圖表的填充樣式屬性。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**傳回:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getLine() {#getLine--}
```
public final ILineFormat getLine()
```

傳回圖表的線條樣式屬性。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**傳回:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getEffect() {#getEffect--}
```
public final IEffectFormat getEffect()
```

傳回圖表使用的效果。唯讀 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**傳回:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getEffect3D() {#getEffect3D--}
```
public final IThreeDFormat getEffect3D()
```

傳回圖表的 3D 格式。唯讀 [IThreeDFormat](../../com.aspose.slides/ithreedformat)。

**傳回:**  
[IThreeDFormat](../../com.aspose.slides/ithreedformat)