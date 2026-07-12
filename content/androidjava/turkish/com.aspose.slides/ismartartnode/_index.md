---
title: ISmartArtNode
second_title: Aspose.Slides for Android via Java API Reference
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
| [getChildNodes()](#getChildNodes--) | Mevcut düğümün tüm alt düğümlerinin koleksiyonlarını döndürür. |
| [getShapes()](#getShapes--) | Düğümle ilişkili tüm şekillerin koleksiyonlarını döndürür. |
| [getTextFrame()](#getTextFrame--) | Düğümün metnini döndürür veya ayarlar. |
| [isAssistant()](#isAssistant--) | Düğümü asistan olarak döndürür veya ayarlar. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Düğümü asistan olarak döndürür veya ayarlar. |
| [getLevel()](#getLevel--) | Düğümün iç içe geçmiş seviyesini döndürür. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Düğüm madde işareti için dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. |
| [getPosition()](#getPosition--) | Kardeş düğümler arasında sıfır tabanlı konumunu döndürür veya ayarlar. |
| [setPosition(int value)](#setPosition-int-) | Kardeş düğümler arasında sıfır tabanlı konumunu döndürür veya ayarlar. |
| [isHidden()](#isHidden--) | Bu düğüm veri modelinde gizli bir düğümse true döndürür. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Mevcut düğümle ilişkili organizasyon şeması düzeni tipini döndürür veya ayarlar. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Mevcut düğümle ilişkili organizasyon şeması düzeni tipini döndürür veya ayarlar. |
| [remove()](#remove--) | Mevcut düğümü kaldır. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```


Mevcut düğümün tüm alt düğümlerinin koleksiyonlarını döndürür. Yalnızca okunabilir [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Döndürür:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```


Düğümle ilişkili tüm şekillerin koleksiyonlarını döndürür. Yalnızca okunabilir [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Döndürür:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Düğümün metnini döndürür veya ayarlar. Yalnızca okunabilir [ITextFrame](../../com.aspose.slides/itextframe).

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```


Düğümü asistan olarak döndürür veya ayarlar. Okunabilir/yazılabilir boolean.

**Döndürür:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```


Düğümü asistan olarak döndürür veya ayarlar. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```


Düğümün iç içe geçmiş seviyesini döndürür. Yalnızca okunabilir int.

**Döndürür:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```


Düğüm madde işareti için dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: Belirli SmartArt düzeni türleri için düğümler madde işareti sağlamadığından null döndürebilir. Yalnızca okunabilir [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Kardeş düğümler arasında sıfır tabanlı konumunu döndürür veya ayarlar. Okunabilir/yazılabilir int.

**Döndürür:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Kardeş düğümler arasında sıfır tabanlı konumunu döndürür veya ayarlar. Okunabilir/yazılabilir int.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```


Bu düğüm veri modelinde gizli bir düğümse true döndürür. Yalnızca okunabilir boolean.

**Döndürür:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```


Mevcut düğümle ilişkili organizasyon şeması düzeni tipini döndürür veya ayarlar. Okunabilir/yazılabilir [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Döndürür:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```


Mevcut düğümle ilişkili organizasyon şeması düzeni tipini döndürür veya ayarlar. Okunabilir/yazılabilir [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```


Mevcut düğümü kaldır.

**Döndürür:**
boolean - kaldırma başarılıysa true, aksi takdirde false.