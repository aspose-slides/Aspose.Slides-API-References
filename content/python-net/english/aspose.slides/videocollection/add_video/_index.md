---
title: add_video method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/videocollection/add_video/
weight: 10
---


## add_video {#ivideo}
Adds a copy of an video file from an another presentation.

### Returns

Added video.



```python
def add_video(self, video):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| video | IVideo | Source video. |



## add_video {#systemiostream}
Creates and adds a video to a presentation from stream.

### Returns

Added [`Video`](/slides/python-net/aspose.slides/video).



```python
def add_video(self, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | System.IO.Stream | Stream to add video file from. |



## add_video {#bytes}
Creates and adds a video to a presentation from byte array.

### Returns

Added video.



```python
def add_video(self, video_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| video_data | bytes | Video bytes. |



## add_video {#systemiostream-loadingstreambehavior}
Creates and adds a video to a presentation from stream.

### Returns

Added [`IVideo`](/slides/python-net/aspose.slides/ivideo).



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | System.IO.Stream | Stream to add video file from. |
| loading_stream_behavior | LoadingStreamBehavior | The behavior which will be applied to the stream. |



### See Also
* class [`IVideo`](/slides/python-net/aspose.slides/ivideo)
* class [`Video`](/slides/python-net/aspose.slides/video)
* class [`VideoCollection`](/slides/python-net/aspose.slides/videocollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
