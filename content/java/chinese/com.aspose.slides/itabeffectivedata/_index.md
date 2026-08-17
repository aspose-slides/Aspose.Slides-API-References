---
title: ITabEffectiveData
second_title: Aspose.Slides for Java API 参考
description: 不可变对象，包含有效文本的制表位属性。
type: docs
url: /zh/com.aspose.slides/itabeffectivedata/
---
**所有实现的接口：**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

不可变对象，包含有效文本的制表位属性。

--------------------

此接口用作 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) 的一部分。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPosition()](#getPosition--) | 返回制表位的位置。 |
| [getAlignment()](#getAlignment--) | 返回制表位的对齐样式。 |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```


返回制表位的位置。赋值此属性可能会更改集合中制表位的索引并使 Enumerator 失效。只读 double.

**返回：**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


返回制表位的对齐样式。只读 [TabAlignment](../../com.aspose.slides/tabalignment)。

**返回：**
int