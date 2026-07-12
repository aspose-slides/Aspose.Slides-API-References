---
title: SmartArt
second_title: Aspose.Slides for Android için Java API Referansı
description: Bir SmartArt diyagramını temsil eder
type: docs
url: /tr/com.aspose.slides/smartart/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ISmartArt](../../com.aspose.slides/ismartart)
```
public class SmartArt extends GraphicalObject implements ISmartArt
```

Bir SmartArt diyagramını temsil eder
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | SmartArt nesnesindeki tüm düğümlerin koleksiyonlarını döndürür. |
| [getNodes()](#getNodes--) | SmartArt nesnesindeki kök düğümlerin koleksiyonlarını döndürür. |
| [getLayout()](#getLayout--) | SmartArt nesnesinin düzenini döndürür veya ayarlar. |
| [setLayout(int value)](#setLayout-int-) | SmartArt nesnesinin düzenini döndürür veya ayarlar. |
| [getQuickStyle()](#getQuickStyle--) | SmartArt nesnesinin hızlı stilini döndürür veya ayarlar. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | SmartArt nesnesinin hızlı stilini döndürür veya ayarlar. |
| [getColorStyle()](#getColorStyle--) | SmartArt nesnesinin renk stilini döndürür veya ayarlar. |
| [setColorStyle(int value)](#setColorStyle-int-) | SmartArt nesnesinin renk stilini döndürür veya ayarlar. |
| [isReversed()](#isReversed--) | Diyagram terslemeyi destekliyorsa, SmartArt diyagramının (soldan sağa) LTR veya (sağdan sola) RTL durumunu döndürür veya ayarlar. |
| [setReversed(boolean value)](#setReversed-boolean-) | Diyagram terslemeyi destekliyorsa, SmartArt diyagramının (soldan sağa) LTR veya (sağdan sola) RTL durumunu döndürür veya ayarlar. |
### getAllNodes() {#getAllNodes--}
```
public final ISmartArtNodeCollection getAllNodes()
```


SmartArt nesnesindeki tüm düğümlerin koleksiyonlarını döndürür. Yalnızca okuma [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Döndürür:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public final ISmartArtNodeCollection getNodes()
```


SmartArt nesnesindeki kök düğümlerin koleksiyonlarını döndürür. Yalnızca okuma [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Döndürür:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public final int getLayout()
```


SmartArt nesnesinin düzenini döndürür veya ayarlar. Okuma/yazma [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Döndürür:**
int
### setLayout(int value) {#setLayout-int-}
```
public final void setLayout(int value)
```


SmartArt nesnesinin düzenini döndürür veya ayarlar. Okuma/yazma [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public final int getQuickStyle()
```


SmartArt nesnesinin hızlı stilini döndürür veya ayarlar. Okuma/yazma [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Döndürür:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public final void setQuickStyle(int value)
```


SmartArt nesnesinin hızlı stilini döndürür veya ayarlar. Okuma/yazma [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public final int getColorStyle()
```


SmartArt nesnesinin renk stilini döndürür veya ayarlar. Okuma/yazma [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Döndürür:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public final void setColorStyle(int value)
```


SmartArt nesnesinin renk stilini döndürür veya ayarlar. Okuma/yazma [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public final boolean isReversed()
```


Diyagram terslemeyi destekliyorsa, SmartArt diyagramının (soldan sağa) LTR veya (sağdan sola) RTL durumunu döndürür veya ayarlar. Okuma/yazma  boolean .

**Döndürür:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public final void setReversed(boolean value)
```


Diyagram terslemeyi destekliyorsa, SmartArt diyagramının (soldan sağa) LTR veya (sağdan sola) RTL durumunu döndürür veya ayarlar. Okuma/yazma  boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |