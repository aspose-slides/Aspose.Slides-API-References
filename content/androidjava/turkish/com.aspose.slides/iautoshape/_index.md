---
title: IAutoShape
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bir AutoShape'i temsil eder.
type: docs
url: /tr/com.aspose.slides/iautoshape/
---
**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Bir AutoShape'i temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Returns AutoShape's locks. |
| [getTextFrame()](#getTextFrame--) | Returns TextFrame object for the AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Adds a new TextFrame to a shape. |
| [isTextBox()](#isTextBox--) | Specifies if the shape is a text box. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```

AutoShape'in kilitlerini döndürür. Salt-okunur [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Döndürür:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

AutoShape için TextFrame nesnesini döndürür. Salt-okunur [ITextFrame](../../com.aspose.slides/itextframe).

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```

Bu autoshape'in slaytın arka plan dolgusuyla mı, stil veya dolgu formatı tarafından belirtilenle mi doldurulması gerektiğini belirler. Okunabilir/Yazılabilir boolean.

**Döndürür:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```

Bu autoshape'in slaytın arka plan dolgusuyla mı, stil veya dolgu formatı tarafından belirtilenle mi doldurulması gerektiğini belirler. Okunabilir/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```

Bir şekle yeni bir TextFrame ekler. Şekil zaten bir TextFrame'e sahipse, sadece metnini değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Yeni bir TextFrame için varsayılan metin. |

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe) - Yeni [ITextFrame](../../com.aspose.slides/itextframe) nesnesi.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```

Şeklin bir metin kutusu olup olmadığını belirtir.

--------------------

Şeklin bir metin kutusu olarak belirtilmemiş olması, ona metin eklenemeyeceği anlamına gelmez. Metin kutusu, yalnızca belirli özelliklere sahip özel bir şekildir.

**Döndürür:**
boolean