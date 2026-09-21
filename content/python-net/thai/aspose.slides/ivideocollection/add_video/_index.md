---
title: add_video method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/ivideocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
เพิ่มสำเนาของไฟล์วิดีโอจากการนำเสนออื่น

### คืนค่า

เพิ่มวิดีโอแล้ว.



```python
def add_video(self, video):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/th/aspose.slides/ivideo) | วิดีโอต้นทาง |


## add_video(self, video_data) {#bytes}
สร้างและเพิ่มวิดีโอไปยังการนำเสนอจากอาร์เรย์ไบต์

### คืนค่า

เพิ่มวิดีโอแล้ว.



```python
def add_video(self, video_data):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| video_data | **bytes** | ไบต์ของวิดีโอ |


## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
สร้างและเพิ่มวิดีโอไปยังการนำเสนอจากสตรีม

### คืนค่า

เพิ่ม [`IVideo`](/slides/python-net/th/aspose.slides/ivideo) แล้ว.



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| stream | **io.RawIOBase** | สตรีมที่ใช้เพิ่มไฟล์วิดีโอ |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/th/aspose.slides/loadingstreambehavior) | พฤติกรรมที่จะใช้กับสตรีม |



### ดูเพิ่มเติม
* คลาส [`IVideo`](/slides/python-net/th/aspose.slides/ivideo)
* คลาส [`IVideoCollection`](/slides/python-net/th/aspose.slides/ivideocollection)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/th/aspose.slides/loadingstreambehavior)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)