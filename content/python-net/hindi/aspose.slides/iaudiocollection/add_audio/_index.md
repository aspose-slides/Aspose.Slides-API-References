---
title: add_audio method
second_title: Aspose.Slides Python के लिये .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/iaudiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
एक अन्य प्रस्तुति से ऑडियो फ़ाइल की प्रतिलिपि जोड़ता है।

### Returns
जोड़ित ऑडियो।

```python
def add_audio(self, audio):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/hi/aspose.slides/iaudio) | स्रोत ऑडियो। |

## add_audio(self, stream) {#iorawiobase}
स्ट्रीम से प्रस्तुति में ऑडियो बनाता है और जोड़ता है।

### Returns
जोड़ित ऑडियो।

```python
def add_audio(self, stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | ऑडियो जोड़ने के लिए स्ट्रीम। |

## add_audio(self, audio_data) {#bytes}
बाइट ऐरे से प्रस्तुति में ऑडियो बनाता है और जोड़ता है।

### Returns
जोड़ित ऑडियो।

```python
def add_audio(self, audio_data):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| audio_data | **bytes** | ऑडियो बाइट्स। |

## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
स्ट्रीम से प्रस्तुति में ऑडियो बनाता है और जोड़ता है।

### Returns
जोड़ित ऑडियो।

```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | वीडियो ऑडियो जोड़ने के लिए स्ट्रीम। |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/hi/aspose.slides/loadingstreambehavior) | स्ट्रीम पर लागू किया जाने वाला व्यवहार। |

### See Also
* class [`IAudio`](/slides/python-net/hi/aspose.slides/iaudio)
* class [`IAudioCollection`](/slides/python-net/hi/aspose.slides/iaudiocollection)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/hi/aspose.slides/loadingstreambehavior)
* module [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)