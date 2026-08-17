---
title: SmartArtNode
second_title: Aspose.Slides Java API Referansı
description: Bir SmartArt nesnesinin düğümünü temsil eder
type: docs
url: /tr/com.aspose.slides/smartartnode/
---
**Kalıtım:**
java.lang.Object

**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

Bir SmartArt nesnesinin düğümünü temsil eder
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Geçerli düğümün tüm alt düğümlerinin koleksiyonlarını döndürür. |
| [getShapes()](#getShapes--) | Düğümle ilişkili tüm şekillerin koleksiyonlarını döndürür. |
| [getTextFrame()](#getTextFrame--) | Düğümün metin çerçevesini döndürür. |
| [isAssistant()](#isAssistant--) | Düğümü asistan olarak döndürür veya ayarlar. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Düğümü asistan olarak döndürür veya ayarlar. |
| [getLevel()](#getLevel--) | Düğümün iç içeleme seviyesini döndürür. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Bir düğüm madde işareti için doldurma biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. |
| [getPosition()](#getPosition--) | Kardeş düğümler arasında düğümün sıfır tabanlı konumunu döndürür veya ayarlar. |
| [setPosition(int value)](#setPosition-int-) | Kardeş düğümler arasında düğümün sıfır tabanlı konumunu döndürür veya ayarlar. |
| [isHidden()](#isHidden--) | Bu düğüm veri modelinde gizli bir düğümse true döndürür. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Geçerli düğümle ilişkili organizasyon şeması yerleşim tipini döndürür veya ayarlar. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Geçerli düğümle ilişkili organizasyon şeması yerleşim tipini döndürür veya ayarlar. |
| [remove()](#remove--) | Geçerli düğümü kaldır. |

### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```


Geçerli düğümün tüm alt düğümlerinin koleksiyonlarını döndürür. Sadece okuma [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Döndürür:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```


Düğümle ilişkili tüm şekillerin koleksiyonlarını döndürür. Sadece okuma [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Döndürür:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


Düğümün metin çerçevesini döndürür. Sadece okuma [ITextFrame](../../com.aspose.slides/itextframe).

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```


Düğümü asistan olarak döndürür veya ayarlar. Okuma/yazma boolean.

**Döndürür:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```


Düğümü asistan olarak döndürür veya ayarlar. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```


Düğümün iç içeleme seviyesini döndürür. Sadece okuma int.

**Döndürür:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```


Bir düğüm madde işareti için doldurma biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: belirli SmartArt yerleşim türleri için, düğümler için madde işaretleri sağlamadığından null döndürebilir. Sadece okuma [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Kardeş düğümler arasında düğümün sıfır tabanlı konumunu döndürür veya ayarlar. Okuma/yazma int .

**Döndürür:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Kardeş düğümler arasında düğümün sıfır tabanlı konumunu döndürür veya ayarlar. Okuma/yazma int .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```


Bu düğüm veri modelinde gizli bir düğümse true döndürür. Sadece okuma boolean.

**Döndürür:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```


Geçerli düğümle ilişkili organizasyon şeması yerleşim tipini döndürür veya ayarlar. Okuma/yazma [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Döndürür:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```


Geçerli düğümle ilişkili organizasyon şeması yerleşim tipini döndürür veya ayarlar. Okuma/yazma [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```


Geçerli düğümü kaldır.

**Döndürür:**
boolean - kaldırma başarılıysa true, aksi takdirde false