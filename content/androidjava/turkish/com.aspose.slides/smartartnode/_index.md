---
title: SmartArtNode
second_title: Android için Java API Referansı aracılığıyla Aspose.Slides
description: Bir SmartArt nesnesinin düğümünü temsil eder
type: docs
url: /tr/com.aspose.slides/smartartnode/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
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
| [getBulletFillFormat()](#getBulletFillFormat--) | Bir düğüm mermisi için dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. |
| [getPosition()](#getPosition--) | Kardeş düğümler arasındaki sıfır-tabanlı konumunu döndürür veya ayarlar. |
| [setPosition(int value)](#setPosition-int-) | Kardeş düğümler arasındaki sıfır-tabanlı konumunu döndürür veya ayarlar. |
| [isHidden()](#isHidden--) | Bu düğüm veri modelinde gizli bir düğümse true döndürür. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Geçerli düğümle ilişkili organizasyon şeması yerleşim tipini döndürür veya ayarlar. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Geçerli düğümle ilişkili organizasyon şeması yerleşim tipini döndürür veya ayarlar. |
| [remove()](#remove--) | Geçerli düğümü kaldır. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

Geçerli düğümün tüm alt düğümlerinin koleksiyonlarını döndürür. Yalnızca-okunur [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Döndürür:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

Düğümle ilişkili tüm şekillerin koleksiyonlarını döndürür. Yalnızca-okunur [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Döndürür:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Düğümün metin çerçevesini döndürür. Yalnızca-okunur [ITextFrame](../../com.aspose.slides/itextframe).

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

Düğümü asistan olarak döndürür veya ayarlar. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

Düğümü asistan olarak döndürür veya ayarlar. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```

Düğümün iç içeleme seviyesini döndürür. Yalnızca-okunur int.

**Döndürür:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

Bir düğüm mermisi için dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: düğümler için mermi sağlamayan belirli SmartArt yerleşim türleri için null dönebilir. Yalnızca-okunur [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Kardeş düğümler arasındaki sıfır-tabanlı konumunu döndürür veya ayarlar. Okunur/yazılır int .

**Döndürür:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Kardeş düğümler arasındaki sıfır-tabanlı konumunu döndürür veya ayarlar. Okunur/yazılır int .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Bu düğüm veri modelinde gizli bir düğümse true döndürür. Yalnızca-okunur boolean.

**Döndürür:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

Geçerli düğümle ilişkili organizasyon şeması yerleşim tipini döndürür veya ayarlar. Okunur/yazılır [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Döndürür:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

Geçerli düğümle ilişkili organizasyon şeması yerleşim tipini döndürür veya ayarlar. Okunur/yazılır [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

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
boolean - başarıyla kaldırıldıysa true, aksi takdirde false