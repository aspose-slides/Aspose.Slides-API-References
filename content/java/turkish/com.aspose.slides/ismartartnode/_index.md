---
title: ISmartArtNode
second_title: Aspose.Slides for Java API Reference
description: Bir SmartArt diyagramının düğümünü temsil eder.
type: docs
url: /tr/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

Bir SmartArt diyagramının düğümünü temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Geçerli düğümün tüm alt düğümlerinin koleksiyonlarını döndürür. |
| [getShapes()](#getShapes--) | Düğümle ilişkili tüm şekillerin koleksiyonlarını döndürür. |
| [getTextFrame()](#getTextFrame--) | Düğümün metnini döndürür veya ayarlar. |
| [isAssistant()](#isAssistant--) | Düğümü asistan olarak döndürür veya ayarlar. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Düğümü asistan olarak döndürür veya ayarlar. |
| [getLevel()](#getLevel--) | Düğümün iç içeleme seviyesini döndürür. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Bir düğüm maddesi için doldurma biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. |
| [getPosition()](#getPosition--) | Düğümün kardeş düğümler arasındaki sıfır tabanlı konumunu döndürür veya ayarlar. |
| [setPosition(int value)](#setPosition-int-) | Düğümün kardeş düğümler arasındaki sıfır tabanlı konumunu döndürür veya ayarlar. |
| [isHidden()](#isHidden--) | Bu düğüm veri modelinde gizli bir düğümse true döndürür. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Geçerli düğümle ilişkili organizasyon şeması düzeni tipini döndürür veya ayarlar. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Geçerli düğümle ilişkili organizasyon şeması düzeni tipini döndürür veya ayarlar. |
| [remove()](#remove--) | Geçerli düğümü kaldır. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```


Geçerli düğümün tüm alt düğümlerinin koleksiyonlarını döndürür. Salt okunur [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Returns:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```


Düğümle ilişkili tüm şekillerin koleksiyonlarını döndürür. Salt okunur [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Returns:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Düğümün metnini döndürür veya ayarlar. Salt okunur [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```


Düğümü asistan olarak döndürür veya ayarlar. Okunabilir/Yazılabilir boolean.

**Returns:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```


Düğümü asistan olarak döndürür veya ayarlar. Okunabilir/Yazılabilir boolean.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```


Düğümün iç içeleme seviyesini döndürür. Salt okunur int.

**Returns:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```


Bir düğüm maddesi için doldurma biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: bazı SmartArt düzen türleri düğmeler için madde işaretleri sağlamadığı için null döndürebilir. Salt okunur [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Düğümün kardeş düğümler arasındaki sıfır tabanlı konumunu döndürür veya ayarlar. Okunabilir/Yazılabilir int.

**Returns:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Düğümün kardeş düğümler arasındaki sıfır tabanlı konumunu döndürür veya ayarlar. Okunabilir/Yazılabilir int.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```


Bu düğüm veri modelinde gizli bir düğümse true döndürür. Salt okunur boolean.

**Returns:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```


Geçerli düğümle ilişkili organizasyon şeması düzeni tipini döndürür veya ayarlar. Okunabilir/Yazılabilir [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Returns:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```


Geçerli düğümle ilişkili organizasyon şeması düzeni tipini döndürür veya ayarlar. Okunabilir/Yazılabilir [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```


Geçerli düğümü kaldır.

**Returns:**
boolean - başarılı bir şekilde kaldırıldıysa true, aksi takdirde false.