---
title: ITabEffectiveData
second_title: Aspose.Slides for Android 的 Java API 參考
description: 不可變物件，包含有效文字的定位停止屬性。
type: docs
url: /zh-hant/com.aspose.slides/itabeffectivedata/
---
**所有已實作的介面：**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

不可變物件，包含有效文字的定位停止屬性。

--------------------

此介面用作 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) 的一部分。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getPosition()](#getPosition--) | 傳回定位鍵的位置。 |
| [getAlignment()](#getAlignment--) | 傳回定位鍵的對齊樣式。 |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```

傳回定位鍵的位置。設定此屬性可能會更改集合中定位鍵的索引，並使列舉器失效。唯讀 double。

**傳回:** 
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

傳回定位鍵的對齊樣式。唯讀 [TabAlignment](../../com.aspose.slides/tabalignment)。

**傳回:** 
int