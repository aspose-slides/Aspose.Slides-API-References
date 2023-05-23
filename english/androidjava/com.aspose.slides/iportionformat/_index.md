---
title: IPortionFormat
second_title: Aspose.Slides for Android via Java API Reference
description: This class contains the text portion formatting properties.
type: docs
weight: 976
url: /androidjava/com.aspose.slides/iportionformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

This class contains the text portion formatting properties. Unlike [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), all properties of this class are writeable.

--------------------

This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".

In order to get the effective formatting parameter values including inherited you need to use [getEffective](../../com.aspose.slides/iportionformat\#getEffective) method which returns a [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) instance.
## Methods

| Method | Description |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Returns or sets bookmark identifier. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Returns or sets bookmark identifier. |
| [getSmartTagClean()](#getSmartTagClean--) | Determines whether the smart tag should be cleaned. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Determines whether the smart tag should be cleaned. |
| [getEffective()](#getEffective--) | Gets effective portion formatting data with the inheritance applied. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```


Returns or sets bookmark identifier. Read/write String.

**Returns:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```


Returns or sets bookmark identifier. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```


Determines whether the smart tag should be cleaned. No inheritance applied. Read/write boolean.

**Returns:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```


Determines whether the smart tag should be cleaned. No inheritance applied. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```


Gets effective portion formatting data with the inheritance applied.

**Returns:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
