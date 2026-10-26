---
title: add_video method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/videocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
เพิ่มสำเนาของไฟล์วิดีโอจากงานนำเสนออื่น

### คืนค่า

วิดีโอที่เพิ่ม.

```python
def add_video(self, video):
    ...
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/th/aspose.slides/ivideo) | วิดีโอต้นฉบับ. |

## add_video(self, video_data) {#bytes}
สร้างและเพิ่มวิดีโอลงในงานนำเสนอจากอาร์เรย์ของไบต์

### คืนค่า

วิดีโอที่เพิ่ม.

```python
def add_video(self, video_data):
    ...
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| video_data | **bytes** | ไบต์ของวิดีโอ. |

## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
สร้างและเพิ่มวิดีโอลงในงานนำเสนอจากสตรีม

### คืนค่า

เพิ่ม [`IVideo`](/slides/python-net/th/aspose.slides/ivideo).

```python
def add_video(self, stream, loading_stream_behavior):
    ...
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| stream | **io.RawIOBase** | สตรีมที่ใช้เพิ่มไฟล์วิดีโอจาก. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/th/aspose.slides/loadingstreambehavior) | พฤติกรรมที่จะนำไปใช้กับสตรีม. |

### ดูเพิ่มเติม
* คลาส [`IVideo`](/slides/python-net/th/aspose.slides/ivideo)
* enum [`LoadingStreamBehavior`](/slides/python-net/th/aspose.slides/loadingstreambehavior)
* คลาส [`VideoCollection`](/slides/python-net/th/aspose.slides/videocollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)