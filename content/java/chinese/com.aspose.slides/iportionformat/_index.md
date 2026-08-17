---
title: IPortionFormat
second_title: Aspose.Slides for Java API 参考
description: 此类包含文本部分的格式属性。
type: docs
url: /zh/com.aspose.slides/iportionformat/
---
**所有已实现的接口：**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

此类包含文本部分的格式属性。与 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 不同，此类的所有属性均可写。

--------------------

此类用于返回和操作为特定文本部分定义的格式属性。这意味着在获取值时不应用继承，因此在大多数情况下您将得到表示“未定义”的值。

为了获取包括继承在内的有效格式参数值，您需要使用 [getEffective](../../com.aspose.slides/iportionformat\#getEffective) 方法，该方法返回一个 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 实例。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | 返回或设置书签标识符。 |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | 返回或设置书签标识符。 |
| [getSmartTagClean()](#getSmartTagClean--) | 确定是否应清除智能标签。 |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | 确定是否应清除智能标签。 |
| [getEffective()](#getEffective--) | 获取已应用继承的有效部分格式数据。 |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

返回或设置书签标识符。可读写 String.

**返回：**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

返回或设置书签标识符。可读写 String.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

确定是否应清除智能标签。未应用继承。可读写 boolean.

**返回：**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

确定是否应清除智能标签。未应用继承。可读写 boolean.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

获取已应用继承的有效部分格式数据。

**返回：**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - 一个 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)。