---
title: SizeF
second_title: Aspose.Slides for Android via Java API Reference
description: Class for describing width and height dimensions in some arbitrary unit with floating-point values.
type: docs
url: /com.aspose.slides.android/sizef/
---
**Inheritance:**
java.lang.Object
```
public class SizeF
```

Class for describing width and height dimensions in some arbitrary unit with floating-point values.
## Constructors

| Constructor | Description |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | Create a new SizeF instance. |
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Get the width of the size. |
| [getHeight()](#getHeight--) | Get the height of the size. |
| [equals(Object obj)](#equals-java.lang.Object-) | Check if this size is equal to another size. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Return the size represented as a string with the format  "WxH"  |
### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Create a new SizeF instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | The width of the size |
| height | float | The height of the size |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Get the width of the size.

**Returns:**
float - width
### getHeight() {#getHeight--}
```
public float getHeight()
```


Get the height of the size.

**Returns:**
float - height
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Check if this size is equal to another size.

Two sizes are equal if and only if both their widths and heights are the same.

For this purpose, the width/height float values are considered to be the same if and only if the method Float\#floatToIntBits(float).floatToIntBits(float) returns the identical  int  value when applied to each.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean -  true  if the objects were equal,  false  otherwise
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Return the size represented as a string with the format  "WxH" 

**Returns:**
java.lang.String - string representation of the size
