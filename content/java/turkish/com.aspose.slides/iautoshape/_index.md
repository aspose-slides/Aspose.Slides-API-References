---
title: IAutoShape
second_title: Aspose.Slides için Java API Referansı
description: AutoShape'i temsil eder.
type: docs
url: /tr/com.aspose.slides/iautoshape/
---
**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Bir AutoShape'i temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | AutoShape'in kilitlerini döndürür. |
| [getTextFrame()](#getTextFrame--) | AutoShape için TextFrame nesnesini döndürür. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Bu autoshape'in stil veya dolgu formatı tarafından belirlenen yerine slaytın arka plan dolgusu ile doldurulup doldurulmayacağını belirler. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Bu autoshape'in stil veya dolgu formatı tarafından belirlenen yerine slaytın arka plan dolgusu ile doldurulup doldurulmayacağını belirler. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Bir şekle yeni bir TextFrame ekler. |
| [isTextBox()](#isTextBox--) | Şeklin bir metin kutusu olup olmadığını belirtir. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


AutoShape'in kilitlerini döndürür. Yalnızca okunur [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Döndürür:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


AutoShape için TextFrame nesnesini döndürür. Yalnızca okunur [ITextFrame](../../com.aspose.slides/itextframe).

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


Bu autoshape'in stil veya dolgu formatı tarafından belirlenen yerine slaytın arka plan dolgusu ile doldurulup doldurulmayacağını belirler. Okunabilir/yazılabilir boolean.

**Döndürür:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


Bu autoshape'in stil veya dolgu formatı tarafından belirlenen yerine slaytın arka plan dolgusu ile doldurulup doldurulmayacağını belirler. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


Bir şekle yeni bir TextFrame ekler. Şekil zaten bir TextFrame içeriyorsa, yalnızca metnini değiştirir.

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

Şeklin bir metin kutusu olarak belirtilmemiş olması, metin eklenemeyeceği anlamına gelmez. Bir metin kutusu yalnızca belirli özelliklere sahip özelleştirilmiş bir şekildir.

**Döndürür:**
boolean