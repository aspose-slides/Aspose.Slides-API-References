---
title: Size
second_title: Aspose.Slides for Android via Java API Reference
description: Class for describing width and height dimensions in some arbitrary unit.
type: docs
weight: 10
url: /androidjava/com.aspose.slides.android/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Class for describing width and height dimensions in some arbitrary unit.
## Constructors

| Constructor | Description |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | Create a new Size instance. |
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Get the width of the size. |
| [getHeight()](#getHeight--) | Get the height of the size. |
| [equals(Object obj)](#equals-java.lang.Object-) | Check if this size is equal to another size. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Return the size represented as a string with the format  "WxH"  |
### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Create a new Size instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width of the size |
| height | int | The height of the size |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Get the width of the size.

**Returns:**
int - width
### getHeight() {#getHeight--}
```
public int getHeight()
```


Get the height of the size.

**Returns:**
int - height
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Check if this size is equal to another size.

Two sizes are equal if and only if both their widths and heights are equal.

A size object is never equal to any other type of object.

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
