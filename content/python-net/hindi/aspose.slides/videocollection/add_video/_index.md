---
title: add_video method
second_title: Aspose.Slides Python के लिए .NET API के माध्यम से संदर्भ
description: 
type: docs
url: /hi/aspose.slides/videocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
एक अन्य प्रस्तुति से वीडियो फ़ाइल की एक प्रति जोड़ता है।

### रिटर्न

जोड़ गया वीडियो।



```python
def add_video(self, video):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/hi/aspose.slides/ivideo) | स्रोत वीडियो। |


## add_video(self, video_data) {#bytes}
बाइट एरे से प्रस्तुति में एक वीडियो बनाता है और जोड़ता है।

### रिटर्न

जोड़ गया वीडियो।



```python
def add_video(self, video_data):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| video_data | **bytes** | वीडियो बाइट्स। |


## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
स्ट्रीम से प्रस्तुति में एक वीडियो बनाता है और जोड़ता है।

### रिटर्न

जोड़ा गया [`IVideo`](/slides/python-net/hi/aspose.slides/ivideo)।



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | **io.RawIOBase** | वीडियो फ़ाइल जोड़ने के लिए स्ट्रीम। |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/hi/aspose.slides/loadingstreambehavior) | स्ट्रीम पर लागू किया जाने वाला व्यवहार। |



### देखें भी
* क्लास [`IVideo`](/slides/python-net/hi/aspose.slides/ivideo)
* एन्यूमरेशन [`LoadingStreamBehavior`](/slides/python-net/hi/aspose.slides/loadingstreambehavior)
* क्लास [`VideoCollection`](/slides/python-net/hi/aspose.slides/videocollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)