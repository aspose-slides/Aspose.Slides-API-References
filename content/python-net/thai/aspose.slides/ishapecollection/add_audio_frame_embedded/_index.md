---
title: add_audio_frame_embedded method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ishapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
สร้างเฟรมเสียงใหม่พร้อมไฟล์ WAV ฝังในตัวและเพิ่มไปยังท้ายของคอลเลกชันรูปทรง เสียงที่ฝังไว้จะถูกเพิ่มไปยังคอลเลกชัน Presentation.Audios

### คืนค่า

[`IAudioFrame`](/slides/python-net/th/aspose.slides/iaudioframe) ที่สร้างใหม่.

```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| x | **float** | พิกัด x ของเฟรมเสียงใหม่, มีหน่วยเป็นจุด. |
| y | **float** | พิกัด y ของเฟรมเสียงใหม่, มีหน่วยเป็นจุด. |
| width | **float** | ความกว้างของเฟรมเสียงใหม่, มีหน่วยเป็นจุด. |
| height | **float** | ความสูงของเฟรมเสียงใหม่, มีหน่วยเป็นจุด. |
| audio_stream | **io.RawIOBase** | สตรีมอินพุตที่มีข้อมูลเสียง WAV เพื่อฝัง. |

## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
สร้างเฟรมเสียงใหม่และเพิ่มไปยังท้ายของคอลเลกชันรูปทรงโดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios

### คืนค่า

[`IAudioFrame`](/slides/python-net/th/aspose.slides/iaudioframe) ที่สร้างใหม่.

```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| x | **float** | พิกัด x ของเฟรมเสียงใหม่, มีหน่วยเป็นจุด. |
| y | **float** | พิกัด y ของเฟรมเสียงใหม่, มีหน่วยเป็นจุด. |
| width | **float** | ความกว้างของเฟรมเสียงใหม่, มีหน่วยเป็นจุด. |
| height | **float** | ความสูงของเฟรมเสียงใหม่, มีหน่วยเป็นจุด. |
| audio | [`IAudio`](/slides/python-net/th/aspose.slides/iaudio) | อินสแตนซ์ของ [`IAudio`](/slides/python-net/th/aspose.slides/iaudio) จากคอลเลกชัน Presentation.Audios. |

### ดูเพิ่มเติม
* คลาส [`IAudio`](/slides/python-net/th/aspose.slides/iaudio)
* คลาส [`IAudioFrame`](/slides/python-net/th/aspose.slides/iaudioframe)
* คลาส [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)