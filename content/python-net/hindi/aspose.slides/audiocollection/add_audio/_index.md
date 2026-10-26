---
title: add_audio method
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/audiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
एक अन्य प्रस्तुति से ऑडियो फ़ाइल की एक प्रति जोड़ता है।

### रिटर्न
जोड़ा गया ऑडियो।

```python
def add_audio(self, audio):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/hi/aspose.slides/iaudio) | स्रोत ऑडियो। |

## add_audio(self, stream) {#iorawiobase}
स्ट्रीम से प्रस्तुति में ऑडियो बनाता है और जोड़ता है।

### रिटर्न
जोड़ा गया ऑडियो।

```python
def add_audio(self, stream):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | **io.RawIOBase** | ऑडियो जोड़ने के लिए स्ट्रीम। |

## add_audio(self, audio_data) {#bytes}
बाइट ऐरे से प्रस्तुति में ऑडियो बनाता है और जोड़ता है।

### रिटर्न
जोड़ा गया ऑडियो।

```python
def add_audio(self, audio_data):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| audio_data | **bytes** | ऑडियो बाइट्स। |

## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
स्ट्रीम से प्रस्तुति में ऑडियो बनाता है और जोड़ता है।

### रिटर्न
जोड़ा गया ऑडियो।

```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | **io.RawIOBase** | वीडियो ऑडियो जोड़ने के लिए स्ट्रीम। |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/hi/aspose.slides/loadingstreambehavior) | स्ट्रीम पर लागू किए जाने वाला व्यवहार। |

### देखें
* वर्ग [`AudioCollection`](/slides/python-net/hi/aspose.slides/audiocollection)
* वर्ग [`IAudio`](/slides/python-net/hi/aspose.slides/iaudio)
* एन्यूमरेशन [`LoadingStreamBehavior`](/slides/python-net/hi/aspose.slides/loadingstreambehavior)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)