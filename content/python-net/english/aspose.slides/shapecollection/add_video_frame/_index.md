﻿---
title: add_video_frame method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/add_video_frame/
weight: 160
---


## add_video_frame {#float-float-float-float-str}
Creates a new video frame and adds it to the end of the shape collection.

### Returns

The newly created [`IVideoFrame`](/slides/python-net/aspose.slides/ivideoframe).



```python
def add_video_frame(self, x, y, width, height, fname):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | The x-coordinate of the new video frame, in points. |
| y | **float** | The y-coordinate of the new video frame, in points. |
| width | **float** | The width of the new video frame, in points. |
| height | **float** | The height of the new video frame, in points. |
| fname | **str** | The path or name of the video file to embed. |


## add_video_frame {#float-float-float-float-ivideo}
Creates a new video frame and adds it to the end of the shape collection.

### Returns

The newly created [`IVideoFrame`](/slides/python-net/aspose.slides/ivideoframe).



```python
def add_video_frame(self, x, y, width, height, video):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | The x-coordinate of the new video frame, in points. |
| y | **float** | The y-coordinate of the new video frame, in points. |
| width | **float** | The width of the new video frame, in points. |
| height | **float** | The height of the new video frame, in points. |
| video | [`IVideo`](/slides/python-net/aspose.slides/ivideo) | The [`IVideo`](/slides/python-net/aspose.slides/ivideo) to embed in the video frame. |



### See Also
* class [`IVideo`](/slides/python-net/aspose.slides/ivideo)
* class [`IVideoFrame`](/slides/python-net/aspose.slides/ivideoframe)
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

