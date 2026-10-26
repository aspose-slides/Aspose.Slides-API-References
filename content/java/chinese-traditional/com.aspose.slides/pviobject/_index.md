---
title: PVIObject
second_title: Aspose.Slides for Java API 參考
description: 封裝了基本的服務基礎結構，供可能成為屬性值繼承主題的物件使用。
type: docs
url: /zh-hant/com.aspose.slides/pviobject/
---
**繼承:**  
java.lang.Object

**全部已實作介面:**  
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

封裝了基本的服務基礎結構，供可能成為屬性值繼承主題的物件使用。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 與指定物件比較。 |
| [hashCode()](#hashCode--) | 傳回雜湊碼。 |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回:**  
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**傳回:**  
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPPresentationComponent getParent_IPresentationComponent()
```

傳回父層 IPresentationComponent。唯讀 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**傳回:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```

**傳回:**  
[ISlideComponent](../../com.aspose.slides/islidecomponent)

### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```

傳回基礎投影片。唯讀 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**傳回:**  
[BaseSlide](../../com.aspose.slides/baseslide)

### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```

傳回簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**傳回:**  
[Presentation](../../com.aspose.slides/presentation)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

與指定物件比較。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的物件。 |

**傳回:**  
boolean - 若物件相等則為 True，否則為 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

傳回雜湊碼。

**傳回:**  
int - 雜湊碼。