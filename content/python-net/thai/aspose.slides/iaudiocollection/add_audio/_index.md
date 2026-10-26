---
title: add_audio method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/iaudiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
เพิ่มสำเนาของไฟล์เสียงจากงานนำเสนออื่น

### ผลลัพธ์
เสียงที่เพิ่มแล้ว.

```python
def add_audio(self, audio):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/th/aspose.slides/iaudio) | ไฟล์เสียงต้นทาง. |

## add_audio(self, stream) {#iorawiobase}
สร้างและเพิ่มเสียงลงในงานนำเสนอจากสตรีม

### ผลลัพธ์
เสียงที่เพิ่มแล้ว.

```python
def add_audio(self, stream):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| stream | **io.RawIOBase** | สตรีมที่จะเพิ่มเสียงจาก. |

## add_audio(self, audio_data) {#bytes}
สร้างและเพิ่มเสียงในงานนำเสนอจากอาร์เรย์ไบต์

### ผลลัพธ์
เสียงที่เพิ่มแล้ว.

```python
def add_audio(self, audio_data):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| audio_data | **bytes** | ไบต์ของไฟล์เสียง. |

## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
สร้างและเพิ่มเสียงลงในงานนำเสนอจากสตรีม

### ผลลัพธ์
เสียงที่เพิ่มแล้ว.

```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| stream | **io.RawIOBase** | สตรีมที่จะเพิ่มเสียงวิดีโอจาก. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/th/aspose.slides/loadingstreambehavior) | พฤติกรรมที่จะนำไปใช้กับสตรีม. |

### ดูเพิ่มเติม
* คลาส [`IAudio`](/slides/python-net/th/aspose.slides/iaudio)
* คลาส [`IAudioCollection`](/slides/python-net/th/aspose.slides/iaudiocollection)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/th/aspose.slides/loadingstreambehavior)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)