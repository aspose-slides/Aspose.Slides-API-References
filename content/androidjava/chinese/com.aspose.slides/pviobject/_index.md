---
title: PVIObject
second_title: Aspose.Slides for Android via Java API 参考
description: 封装对象的基本服务基础设施，可作为属性值继承的主体。
type: docs
url: /zh/com.aspose.slides/pviobject/
---
**继承:**
java.lang.Object

**所有实现的接口:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

封装对象的基本服务基础设施，可作为属性值继承的主体。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 与指定对象比较。 |
| [hashCode()](#hashCode--) | 返回哈希码。 |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```

返回父级 IPresentationComponent。只读 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

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

返回基础幻灯片。只读 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**返回:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```

返回演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回:**
[Presentation](../../com.aspose.slides/presentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

与指定对象比较。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的对象。 |

**返回:**
boolean - 若对象相等返回 true，否则返回 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

返回哈希码。

**返回:**
int - 哈希码.