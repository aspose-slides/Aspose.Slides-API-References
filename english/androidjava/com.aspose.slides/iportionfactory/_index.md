---
title: IPortionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create test portions
type: docs
weight: 975
url: /androidjava/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Allows to create test portions

--------------------

For COM comparibility
## Methods

| Method | Description |
| --- | --- |
| [createPortion()](#createPortion--) | Creates an empty text portion. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Creates a text portion from specified string. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Creates a portion with the using of a specified portion data. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


Creates an empty text portion.

**Returns:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```


Creates a text portion from specified string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String | String. |

**Returns:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```


Creates a portion with the using of a specified portion data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | A portion to use. |

**Returns:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
