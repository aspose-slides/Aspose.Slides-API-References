---
title: PathSegment
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents segment of graphics path of GeometryShape
type: docs
weight: 404
url: /java/com.aspose.slides/pathsegment/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPathSegment](../../com.aspose.slides/ipathsegment)
```
public final class PathSegment implements IPathSegment
```

Represents segment of graphics path of GeometryShape
## Constructors

| Constructor | Description |
| --- | --- |
| [PathSegment(byte pathType, float[] segmentData)](#PathSegment-byte-float---) |  |
## Methods

| Method | Description |
| --- | --- |
| [getSegmentData()](#getSegmentData--) | Path data of the segment |
| [getPathCommand()](#getPathCommand--) | Path type of the segment |
### PathSegment(byte pathType, float[] segmentData) {#PathSegment-byte-float---}
```
 PathSegment(byte pathType, float[] segmentData)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pathType | byte |  |
| segmentData | float[] |  |

### getSegmentData() {#getSegmentData--}
```
public final float[] getSegmentData()
```


Path data of the segment

**Returns:**
float[]
### getPathCommand() {#getPathCommand--}
```
public final byte getPathCommand()
```


Path type of the segment

**Returns:**
byte
