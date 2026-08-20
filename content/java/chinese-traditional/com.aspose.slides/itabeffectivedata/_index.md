---
title: ITabEffectiveData
second_title: Aspose.Slides for Java API 參考
description: 不可變的物件，包含有效文字的定位點屬性。
type: docs
url: /zh-hant/com.aspose.slides/itabeffectivedata/
---
**已實作的介面：**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

不可變物件，包含有效文字的定位點屬性。

--------------------

此介面用作 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) 的一部分。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPosition()](#getPosition--) | 傳回定位點的位置。 |
| [getAlignment()](#getAlignment--) | 傳回定位點的對齊樣式。 |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```

傳回定位點的位置。指派此屬性可能會變更集合中定位點的索引，並使列舉器失效。唯讀 double。

**傳回值：**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

傳回定位點的對齊樣式。唯讀 [TabAlignment](../../com.aspose.slides/tabalignment)。

**傳回值：**
int