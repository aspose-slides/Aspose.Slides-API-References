---
title: add_audio_frame_embedded method
second_title: Aspose.Slides के लिए Python .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ishapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
एक एम्बेडेड WAV फ़ाइल के साथ नया ऑडियो फ़्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है। एम्बेडेड ऑडियो को Presentation.Audios संग्रह में जोड़ा जाता है।

### वापसी मान

नया बनाया गया [`IAudioFrame`](/slides/python-net/hi/aspose.slides/iaudioframe)।

```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| x | **float** | नए ऑडियो फ़्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए ऑडियो फ़्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए ऑडियो फ़्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए ऑडियो फ़्रेम की ऊँचाई, पॉइंट्स में। |
| audio_stream | **io.RawIOBase** | एक इनपुट स्ट्रीम जिसमें एम्बेड करने के लिए WAV ऑडियो डेटा हो। |

## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
एक नया ऑडियो फ़्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है, Presentation.Audios सूची से मौजूद ऑडियो ऑब्जेक्ट का उपयोग करके।

### वापसी मान

नया बनाया गया [`IAudioFrame`](/slides/python-net/hi/aspose.slides/iaudioframe)।

```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| x | **float** | नए ऑडियो फ़्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए ऑडियो फ़्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए ऑडियो फ़्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए ऑडियो फ़्रेम की ऊँचाई, पॉइंट्स में। |
| audio | [`IAudio`](/slides/python-net/hi/aspose.slides/iaudio) | Presentation.Audios संग्रह से एक [`IAudio`](/slides/python-net/hi/aspose.slides/iaudio) उदाहरण। |

### संबंधित देखें
* क्लास [`IAudio`](/slides/python-net/hi/aspose.slides/iaudio)
* क्लास [`IAudioFrame`](/slides/python-net/hi/aspose.slides/iaudioframe)
* क्लास [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)