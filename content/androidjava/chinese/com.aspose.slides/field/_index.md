---
title: Field
second_title: 适用于 Android 的 Aspose.Slides via Java API 参考
description: 表示一个字段。
type: docs
url: /zh/com.aspose.slides/field/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IField](../../com.aspose.slides/ifield)
```
public final class Field extends DomObject<Portion> implements IField
```

表示一个字段。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 返回或设置字段的类型。 |
| [setType(IFieldType value)](#setType-com.aspose.slides.IFieldType-) | 返回或设置字段的类型。 |
| [getSlide()](#getSlide--) | 返回段落的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回段落的父演示文稿。 |
### getType() {#getType--}
```
public final IFieldType getType()
```


返回或设置字段的类型。读写 [IFieldType](../../com.aspose.slides/ifieldtype)。

**返回:**
[IFieldType](../../com.aspose.slides/ifieldtype)
### setType(IFieldType value) {#setType-com.aspose.slides.IFieldType-}
```
public final void setType(IFieldType value)
```


返回或设置字段的类型。读写 [IFieldType](../../com.aspose.slides/ifieldtype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


返回段落的父幻灯片。只读 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


返回段落的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回:**
[IPresentation](../../com.aspose.slides/ipresentation)