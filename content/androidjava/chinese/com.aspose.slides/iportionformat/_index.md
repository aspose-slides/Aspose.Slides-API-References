---
title: IPortionFormat
second_title: Aspose.Slides for Android via Java API 参考
description: 此类包含文本段落格式属性。
type: docs
url: /zh/com.aspose.slides/iportionformat/
---
**所有已实现的接口：**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

此类包含文本段落格式属性。与 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 不同，此类的所有属性均可写。

--------------------

此类用于返回和操作为特定段落定义的文本段落格式属性。这意味着在获取值时不应用继承，因此在大多数情况下您将获得“未定义”的值。

若要获取包括继承在内的有效格式参数值，需要使用 [getEffective](../../com.aspose.slides/iportionformat\#getEffective) 方法，该方法返回一个 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 实例。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | 返回或设置书签标识符。 |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | 返回或设置书签标识符。 |
| [getSmartTagClean()](#getSmartTagClean--) | 确定是否应清除智能标签。 |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | 确定是否应清除智能标签。 |
| [getEffective()](#getEffective--) | 获取在应用继承后的有效段落格式数据。 |

### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

返回或设置书签标识符。读取/写入 String。

**返回值：**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

返回或设置书签标识符。读取/写入 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

确定是否应清除智能标签。未应用继承。读取/写入 boolean。

**返回值：**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

确定是否应清除智能标签。未应用继承。读取/写入 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

获取在应用继承后的有效段落格式数据。

**返回值：**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - 一个 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).