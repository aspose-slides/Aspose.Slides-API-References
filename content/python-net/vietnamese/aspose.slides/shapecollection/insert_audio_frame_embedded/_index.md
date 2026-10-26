---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/shapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Tạo một khung âm thanh mới với tệp WAV được nhúng và chèn nó vào bộ sưu tập shape tại chỉ mục được chỉ định. Âm thanh được nhúng sẽ được thêm vào bộ sưu tập Presentation.Audios.

### Returns

The newly created [`IAudioFrame`](/slides/python-net/vi/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục dựa trên số 0 mà tại đó chèn khung âm thanh. |
| x | **float** | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | **float** | Chiều rộng của khung âm thanh mới, tính bằng điểm. |
| height | **float** | Chiều cao của khung âm thanh mới, tính bằng điểm. |
| audio_stream | **io.RawIOBase** | Luồng đầu vào chứa dữ liệu âm thanh WAV để nhúng. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Tạo một khung âm thanh mới và chèn nó vào bộ sưu tập shape tại chỉ mục được chỉ định bằng cách sử dụng một đối tượng âm thanh hiện có từ danh sách Presentation.Audios.

### Returns

The newly created [`IAudioFrame`](/slides/python-net/vi/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục dựa trên số 0 mà tại đó chèn khung âm thanh. |
| x | **float** | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | **float** | Chiều rộng của khung âm thanh mới, tính bằng điểm. |
| height | **float** | Chiều cao của khung âm thanh mới, tính bằng điểm. |
| audio | [`IAudio`](/slides/python-net/vi/aspose.slides/iaudio) | Một thể hiện [`IAudio`](/slides/python-net/vi/aspose.slides/iaudio) từ bộ sưu tập Presentation.Audios để nhúng. |


### Xem Thêm
* class [`IAudio`](/slides/python-net/vi/aspose.slides/iaudio)
* class [`IAudioFrame`](/slides/python-net/vi/aspose.slides/iaudioframe)
* class [`ShapeCollection`](/slides/python-net/vi/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)