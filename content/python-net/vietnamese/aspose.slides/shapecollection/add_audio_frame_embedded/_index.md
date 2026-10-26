---
title: add_audio_frame_embedded method
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/shapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
Tạo một khung âm thanh mới với tệp WAV được nhúng và thêm nó vào cuối
            bộ sưu tập shape. Âm thanh được nhúng sẽ được thêm vào bộ sưu tập Presentation.Audios.

### Trả về

[`IAudioFrame`](/slides/python-net/vi/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x | **float** | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | **float** | Độ rộng của khung âm thanh mới, tính bằng điểm. |
| height | **float** | Độ cao của khung âm thanh mới, tính bằng điểm. |
| audio_stream | **io.RawIOBase** | Luồng đầu vào chứa dữ liệu âm thanh WAV để nhúng. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
Tạo một khung âm thanh mới và thêm nó vào cuối bộ sưu tập shape bằng cách
            sử dụng một đối tượng âm thanh hiện có trong danh sách Presentation.Audios.

### Trả về

[`IAudioFrame`](/slides/python-net/vi/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x | **float** | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | **float** | Độ rộng của khung âm thanh mới, tính bằng điểm. |
| height | **float** | Độ cao của khung âm thanh mới, tính bằng điểm. |
| audio | [`IAudio`](/slides/python-net/vi/aspose.slides/iaudio) | Một thể hiện [`IAudio`](/slides/python-net/vi/aspose.slides/iaudio) từ bộ sưu tập Presentation.Audios. |



### Xem Thêm
* lớp [`IAudio`](/slides/python-net/vi/aspose.slides/iaudio)
* lớp [`IAudioFrame`](/slides/python-net/vi/aspose.slides/iaudioframe)
* lớp [`ShapeCollection`](/slides/python-net/vi/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)