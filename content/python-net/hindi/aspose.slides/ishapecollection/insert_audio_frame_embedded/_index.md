---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides के लिए Python विया .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
नया ऑडियो फ्रेम बनाता है जिसमें एम्बेडेड WAV फ़ाइल होती है और इसे निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। एम्बेडेड ऑडियो Presentation.Audios संग्रह में जोड़ा जाता है।

### वापसी
The newly created [`IAudioFrame`](/slides/python-net/hi/aspose.slides/iaudioframe).

```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | वह शून्य-आधारित इंडेक्स जहाँ ऑडियो फ्रेम डाला जाना है। |
| x | **float** | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए ऑडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| audio_stream | **io.RawIOBase** | WAV ऑडियो डेटा वाली इनपुट स्ट्रीम जिसे एम्बेड किया जाना है। |

## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
नया ऑडियो फ्रेम बनाता है और इसे shape संग्रह में निर्दिष्ट इंडेक्स पर सम्मिलित करता है, Presentation.Audios सूची से मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करते हुए।

### वापसी
The newly created [`IAudioFrame`](/slides/python-net/hi/aspose.slides/iaudioframe).

```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | वह शून्य-आधारित इंडेक्स जहाँ ऑडियो फ्रेम डाला जाना है। |
| x | **float** | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए ऑडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| audio | [`IAudio`](/slides/python-net/hi/aspose.slides/iaudio) | Presentation.Audios संग्रह से एक [`IAudio`](/slides/python-net/hi/aspose.slides/iaudio) उदाहरण जिसे एम्बेड किया जाएगा। |

### संबंधित देखें
* क्लास [`IAudio`](/slides/python-net/hi/aspose.slides/iaudio)
* क्लास [`IAudioFrame`](/slides/python-net/hi/aspose.slides/iaudioframe)
* क्लास [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)