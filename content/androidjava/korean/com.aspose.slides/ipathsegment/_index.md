---
title: IPathSegment
second_title: Aspose.Slides for Android via Java API Reference
description: Represents segment of graphics path of GeometryShape
type: docs
url: /ko/com.aspose.slides/ipathsegment/
---```
public interface IPathSegment
```

GeometryShape의 그래픽 경로 세그먼트를 나타냅니다
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSegmentData()](#getSegmentData--) | 세그먼트의 경로 데이터 |
| [getPathCommand()](#getPathCommand--) | 세그먼트의 경로 유형 |
### getSegmentData() {#getSegmentData--}
```
public abstract float[] getSegmentData()
```


세그먼트의 경로 데이터

**반환값:**
float[]
### getPathCommand() {#getPathCommand--}
```
public abstract byte getPathCommand()
```


세그먼트의 경로 유형

**반환값:**
byte