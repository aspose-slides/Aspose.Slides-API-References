---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/shapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
एक नया ऑडियो फ्रेम बनाता है जिसमें एम्बेडेड WAV फ़ाइल हो और इसे निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। एम्बेडेड ऑडियो को Presentation.Audios संग्रह में जोड़ा जाता है।

### रिटर्न

नया बनाया गया [`IAudioFrame`](/slides/python-net/hi/aspose.slides/iaudioframe)।



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| index | **int** | वह शून्य-आधारित इंडेक्स जहाँ ऑडियो फ्रेम डालना है। |
| x | **float** | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए ऑडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| audio_stream | **io.RawIOBase** | WAV ऑडियो डेटा वाली इनपुट स्ट्रीम जिसे एम्बेड करना है। |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
एक नया ऑडियो फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है, Presentation.Audios सूची से मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके।

### रिटर्न

नया बनाया गया [`IAudioFrame`](/slides/python-net/hi/aspose.slides/iaudioframe)।



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| index | **int** | वह शून्य-आधारित इंडेक्स जहाँ ऑडियो फ्रेम डालना है। |
| x | **float** | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए ऑडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| audio | [`IAudio`](/slides/python-net/hi/aspose.slides/iaudio) | Presentation.Audios संग्रह से एक [`IAudio`](/slides/python-net/hi/aspose.slides/iaudio) इंस्टेंस जिसे एम्बेड करना है। |



### संबंधित देखें
* class [`IAudio`](/slides/python-net/hi/aspose.slides/iaudio)
* class [`IAudioFrame`](/slides/python-net/hi/aspose.slides/iaudioframe)
* class [`ShapeCollection`](/slides/python-net/hi/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)