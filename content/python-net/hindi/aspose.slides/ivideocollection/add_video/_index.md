---
title: add_video method
second_title: Aspose.Slides Python के लिए .NET API रेफ़रेंस के माध्यम से
description: 
type: docs
url: /hi/aspose.slides/ivideocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
एक अन्य प्रस्तुति से वीडियो फ़ाइल की एक कॉपी जोड़ता है।

### रिटर्न
जोड़ा गया video.



```python
def add_video(self, video):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/hi/aspose.slides/ivideo) | स्रोत video. |


## add_video(self, video_data) {#bytes}
बाइट एरे से प्रस्तुति में एक वीडियो बनाता है और जोड़ता है।

### रिटर्न
जोड़ा गया video.



```python
def add_video(self, video_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| video_data | **bytes** | Video बाइट्स। |


## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
स्ट्रीम से प्रस्तुति में एक वीडियो बनाता है और जोड़ता है।

### रिटर्न
जोड़ा गया [`IVideo`](/slides/python-net/hi/aspose.slides/ivideo).



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | स्ट्रीम जिससे video फ़ाइल जोड़ी जाए। |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/hi/aspose.slides/loadingstreambehavior) | स्ट्रीम पर लागू किया जाएगा ऐसा व्यवहार। |



### देखें भी
* क्लास [`IVideo`](/slides/python-net/hi/aspose.slides/ivideo)
* क्लास [`IVideoCollection`](/slides/python-net/hi/aspose.slides/ivideocollection)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/hi/aspose.slides/loadingstreambehavior)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)