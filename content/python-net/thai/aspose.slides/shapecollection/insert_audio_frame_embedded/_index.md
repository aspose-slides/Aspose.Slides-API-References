---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/shapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
สร้าง audio frame ใหม่ที่ฝังไฟล์ WAV ไว้และแทรกลงในคอลเลกชัน shape ที่ตำแหน่งที่ระบุ ไฟล์เสียงที่ฝังจะถูกเพิ่มเข้าไปในคอลเลกชัน Presentation.Audios

### ผลลัพธ์

อินสแตนซ์ [`IAudioFrame`](/slides/python-net/th/aspose.slides/iaudioframe) ที่สร้างใหม่.

```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีที่เริ่มจากศูนย์ซึ่งใช้เพื่อแทรก audio frame |
| x | **float** | พิกัด x ของ audio frame ใหม่ หน่วยเป็น point |
| y | **float** | พิกัด y ของ audio frame ใหม่ หน่วยเป็น point |
| width | **float** | ความกว้างของ audio frame ใหม่ หน่วยเป็น point |
| height | **float** | ความสูงของ audio frame ใหม่ หน่วยเป็น point |
| audio_stream | **io.RawIOBase** | สตรีมอินพุตที่มีข้อมูลเสียง WAV สำหรับฝัง |

## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
สร้าง audio frame ใหม่และแทรกลงในคอลเลกชัน shape ที่ตำแหน่งที่ระบุ โดยใช้วัตถุ audio ที่มีอยู่จากรายการ Presentation.Audios

### ผลลัพธ์

อินสแตนซ์ [`IAudioFrame`](/slides/python-net/th/aspose.slides/iaudioframe) ที่สร้างใหม่.

```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีที่เริ่มจากศูนย์ซึ่งใช้เพื่อแทรก audio frame |
| x | **float** | พิกัด x ของ audio frame ใหม่ หน่วยเป็น point |
| y | **float** | พิกัด y ของ audio frame ใหม่ หน่วยเป็น point |
| width | **float** | ความกว้างของ audio frame ใหม่ หน่วยเป็น point |
| height | **float** | ความสูงของ audio frame ใหม่ หน่วยเป็น point |
| audio | [`IAudio`](/slides/python-net/th/aspose.slides/iaudio) | อินสแตนซ์ของ [`IAudio`](/slides/python-net/th/aspose.slides/iaudio) จากคอลเลกชัน Presentation.Audios เพื่อฝัง |

### ดูเพิ่มเติม
* คลาส [`IAudio`](/slides/python-net/th/aspose.slides/iaudio)
* คลาส [`IAudioFrame`](/slides/python-net/th/aspose.slides/iaudioframe)
* คลาส [`ShapeCollection`](/slides/python-net/th/aspose.slides/shapecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)