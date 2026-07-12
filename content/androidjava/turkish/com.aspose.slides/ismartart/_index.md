---
title: ISmartArt
second_title: Aspose.Slides Android için Java API Referansı
description: Bir SmartArt diyagramını temsil eder.
type: docs
url: /tr/com.aspose.slides/ismartart/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

Bir SmartArt diyagramını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | SmartArt nesnesindeki tüm düğümlerin koleksiyonlarını döndürür. |
| [getNodes()](#getNodes--) | SmartArt nesnesindeki kök düğümlerin koleksiyonlarını döndürür. |
| [getLayout()](#getLayout--) | SmartArt nesnesinin yerleşimini alır veya ayarlar. |
| [setLayout(int value)](#setLayout-int-) | SmartArt nesnesinin yerleşimini alır veya ayarlar. |
| [getQuickStyle()](#getQuickStyle--) | SmartArt nesnesinin hızlı stilini alır veya ayarlar. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | SmartArt nesnesinin hızlı stilini alır veya ayarlar. |
| [getColorStyle()](#getColorStyle--) | SmartArt nesnesinin renk stilini alır veya ayarlar. |
| [setColorStyle(int value)](#setColorStyle-int-) | SmartArt nesnesinin renk stilini alır veya ayarlar. |
| [isReversed()](#isReversed--) | SmartArt diyagramının (soldan sağa) LTR veya (sağdan sola) RTL durumunu, diyagram tersine çevirmeyi destekliyorsa, alır veya ayarlar. |
| [setReversed(boolean value)](#setReversed-boolean-) | SmartArt diyagramının (soldan sağa) LTR veya (sağdan sola) RTL durumunu, diyagram tersine çevirmeyi destekliyorsa, alır veya ayarlar. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```


SmartArt nesnesindeki tüm düğümlerin koleksiyonlarını döndürür. Salt okunur [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Döndürür:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```


SmartArt nesnesindeki kök düğümlerin koleksiyonlarını döndürür. Salt okunur [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Döndürür:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


SmartArt nesnesinin yerleşimini alır veya ayarlar. Okunur/Yazılır [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Döndürür:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```


SmartArt nesnesinin yerleşimini alır veya ayarlar. Okunur/Yazılır [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```


SmartArt nesnesinin hızlı stilini alır veya ayarlar. Okunur/Yazılır [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Döndürür:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```


SmartArt nesnesinin hızlı stilini alır veya ayarlar. Okunur/Yazılır [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```


SmartArt nesnesinin renk stilini alır veya ayarlar. Okunur/Yazılır [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Döndürür:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```


SmartArt nesnesinin renk stilini alır veya ayarlar. Okunur/Yazılır [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```


SmartArt diyagramının (soldan sağa) LTR veya (sağdan sola) RTL durumunu, diyagram tersine çevirmeyi destekliyorsa, alır veya ayarlar. Okunur/Yazılır boolean.

**Döndürür:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```


SmartArt diyagramının (soldan sağa) LTR veya (sağdan sola) RTL durumunu, diyagram tersine çevirmeyi destekliyorsa, alır veya ayarlar. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |