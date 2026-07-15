---
title: PVIObject
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 封裝了物件可能成為屬性值繼承主體的基本服務基礎設施。
type: docs
url: /zh-hant/com.aspose.slides/pviobject/
---
**繼承:**  
java.lang.Object

**已實作的介面:**  
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)  
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

封裝了物件可能成為屬性值繼承主體的基本服務基礎設施。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 與指定的物件比較。 |
| [hashCode()](#hashCode--) | 返回雜湊碼。 |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回:**  
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**返回:**  
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```

返回父級 IPresentationComponent。唯讀 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**返回:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```

**返回:**  
[ISlideComponent](../../com.aspose.slides/islidecomponent)

### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```

返回基礎投影片。唯讀 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**返回:**  
[BaseSlide](../../com.aspose.slides/baseslide)

### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```

返回簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回:**  
[Presentation](../../com.aspose.slides/presentation)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

與指定的物件比較。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的物件。 |

**返回:**  
boolean - 如果物件相等則返回 true，否則返回 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

返回雜湊碼。

**返回:**  
int - 雜湊碼。