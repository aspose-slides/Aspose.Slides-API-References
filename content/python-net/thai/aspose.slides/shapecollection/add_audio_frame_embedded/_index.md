---
title: add_audio_frame_embedded method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/shapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
สร้างเฟรมเสียงใหม่พร้อมไฟล์ WAV ที่ฝังไว้และเพิ่มเข้าไปในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง เสียงที่ฝังจะถูกเพิ่มไปยังคอลเลกชัน Presentation.Audios

### คืนค่า

อ็อบเจกต์ที่สร้างใหม่ [`IAudioFrame`](/slides/python-net/th/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| x | **float** | พิกัด x ของเฟรมเสียงใหม่ หน่วยเป็นจุด. |
| y | **float** | พิกัด y ของเฟรมเสียงใหม่ หน่วยเป็นจุด. |
| width | **float** | ความกว้างของเฟรมเสียงใหม่ หน่วยเป็นจุด. |
| height | **float** | ความสูงของเฟรมเสียงใหม่ หน่วยเป็นจุด. |
| audio_stream | **io.RawIOBase** | สตรีมอินพุตที่มีข้อมูลเสียง WAV เพื่อฝัง. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
สร้างเฟรมเสียงใหม่และเพิ่มเข้าไปในตำแหน่งสุดท้ายของคอลเลกชันรูปทรงโดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios

### คืนค่า

อ็อบเจกต์ที่สร้างใหม่ [`IAudioFrame`](/slides/python-net/th/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| x | **float** | พิกัด x ของเฟรมเสียงใหม่ หน่วยเป็นจุด. |
| y | **float** | พิกัด y ของเฟรมเสียงใหม่ หน่วยเป็นจุด. |
| width | **float** | ความกว้างของเฟรมเสียงใหม่ หน่วยเป็นจุด. |
| height | **float** | ความสูงของเฟรมเสียงใหม่ หน่วยเป็นจุด. |
| audio | [`IAudio`](/slides/python-net/th/aspose.slides/iaudio) | เป็นอินสแตนซ์ของ [`IAudio`](/slides/python-net/th/aspose.slides/iaudio) จากคอลเลกชัน Presentation.Audios. |



### ดูเพิ่มเติม
* คลาส [`IAudio`](/slides/python-net/th/aspose.slides/iaudio)
* คลาส [`IAudioFrame`](/slides/python-net/th/aspose.slides/iaudioframe)
* คลาส [`ShapeCollection`](/slides/python-net/th/aspose.slides/shapecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)