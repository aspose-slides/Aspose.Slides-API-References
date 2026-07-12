---
title: SmartArtShape
second_title: Aspose.Slides for Android için Java API Referansı
description: SmartArt şekli temsil eder
type: docs
url: /tr/com.aspose.slides/smartartshape/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ISmartArtShape](../../com.aspose.slides/ismartartshape)
```
public class SmartArtShape extends GeometryShape implements ISmartArtShape
```

SmartArt şekli temsil eder
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getShapeType()](#getShapeType--) | Geometri ön ayar tipini döndürür veya ayarlar. |
| [setShapeType(int value)](#setShapeType-int-) | Geometri ön ayar tipini döndürür veya ayarlar. |
| [getTextFrame()](#getTextFrame--) | SmartArt şeklinin metnini döndürür. |
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Geometri ön ayar tipini döndürür veya ayarlar. Not: değer değiştirildiğinde tüm ayar değerleri varsayılan değerlerine sıfırlanır. Okunur/Yazılabilir [ShapeType](../../com.aspose.slides/shapetype).

**Döndürür:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Geometri ön ayar tipini döndürür veya ayarlar. Not: değer değiştirildiğinde tüm ayar değerleri varsayılan değerlerine sıfırlanır. Okunur/Yazılabilir [ShapeType](../../com.aspose.slides/shapetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


SmartArt şeklinin metnini döndürür. Salt okunur [ITextFrame](../../com.aspose.slides/itextframe).

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)