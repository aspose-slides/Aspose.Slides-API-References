---
title: ITabEffectiveData
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 包含有效文本制表位属性的不可变对象。
type: docs
url: /zh/com.aspose.slides/itabeffectivedata/
---
**所有实现的接口：**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

包含有效文本制表位属性的不可变对象。

--------------------

此接口作为 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) 的一部分使用。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPosition()](#getPosition--) | 返回制表符的位置。 |
| [getAlignment()](#getAlignment--) | 返回制表符的对齐样式。 |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```


返回制表符的位置。为此属性赋值可能会更改制表符在集合中的索引并使 Enumerator 失效。只读 double.

**返回值:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


返回制表符的对齐样式。只读 [TabAlignment](../../com.aspose.slides/tabalignment)。

**返回值:**
int