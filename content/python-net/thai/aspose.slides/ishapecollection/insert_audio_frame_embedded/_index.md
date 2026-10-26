---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
สร้าง audio frame ใหม่ที่ฝังไฟล์ WAV ไว้และแทรกเข้าไปในคอลเลกชัน shape ที่ตำแหน่งที่ระบุ ไฟล์เสียงที่ฝังไว้จะถูกเพิ่มเข้าไปในคอลเลกชัน Presentation.Audios

### ส่งคืน

The newly created [`IAudioFrame`](/slides/python-net/th/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีที่เริ่มจากศูนย์ซึ่งใช้เพื่อแทรก audio frame |
| x | **float** | ค่าพิกัด x ของ audio frame ใหม่ หน่วยเป็นจุด |
| y | **float** | ค่าพิกัด y ของ audio frame ใหม่ หน่วยเป็นจุด |
| width | **float** | ความกว้างของ audio frame ใหม่ หน่วยเป็นจุด |
| height | **float** | ความสูงของ audio frame ใหม่ หน่วยเป็นจุด |
| audio_stream | **io.RawIOBase** | สตรีมอินพุตที่มีข้อมูลเสียง WAV เพื่อฝัง |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
สร้าง audio frame ใหม่และแทรกเข้าไปในคอลเลกชัน shape ที่ตำแหน่งที่ระบุโดยใช้วัตถุ audio ที่มีอยู่จากรายการ Presentation.Audios

### ส่งคืน

The newly created [`IAudioFrame`](/slides/python-net/th/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีที่เริ่มจากศูนย์ซึ่งใช้เพื่อแทรก audio frame |
| x | **float** | ค่าพิกัด x ของ audio frame ใหม่ หน่วยเป็นจุด |
| y | **float** | ค่าพิกัด y ของ audio frame ใหม่ หน่วยเป็นจุด |
| width | **float** | ความกว้างของ audio frame ใหม่ หน่วยเป็นจุด |
| height | **float** | ความสูงของ audio frame ใหม่ หน่วยเป็นจุด |
| audio | [`IAudio`](/slides/python-net/th/aspose.slides/iaudio) | อินสแตนซ์ของ [`IAudio`](/slides/python-net/th/aspose.slides/iaudio) จากคอลเลกชัน Presentation.Audios เพื่อฝัง |



### ดูเพิ่มเติม
* คลาส [`IAudio`](/slides/python-net/th/aspose.slides/iaudio)
* คลาส [`IAudioFrame`](/slides/python-net/th/aspose.slides/iaudioframe)
* คลาส [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)