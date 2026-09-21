---
title: insert_audio_frame_embedded method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Tạo một khung âm thanh mới với tệp WAV được nhúng và chèn nó vào bộ sưu tập shape tại vị trí chỉ định. Âm thanh được nhúng sẽ được thêm vào bộ sưu tập Presentation.Audios.

### Returns

Đối tượng [`IAudioFrame`](/slides/python-net/vi/aspose.slides/iaudioframe) mới được tạo.



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục bắt đầu từ 0, vị trí cần chèn khung âm thanh. |
| x | **float** | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | **float** | Độ rộng của khung âm thanh mới, tính bằng điểm. |
| height | **float** | Độ cao của khung âm thanh mới, tính bằng điểm. |
| audio_stream | **io.RawIOBase** | Luồng đầu vào chứa dữ liệu âm thanh WAV để nhúng. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Tạo một khung âm thanh mới và chèn nó vào bộ sưu tập shape tại vị trí chỉ định bằng cách sử dụng một đối tượng âm thanh đã có trong danh sách Presentation.Audios.

### Returns

Đối tượng [`IAudioFrame`](/slides/python-net/vi/aspose.slides/iaudioframe) mới được tạo.



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục bắt đầu từ 0, vị trí cần chèn khung âm thanh. |
| x | **float** | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | **float** | Độ rộng của khung âm thanh mới, tính bằng điểm. |
| height | **float** | Độ cao của khung âm thanh mới, tính bằng điểm. |
| audio | [`IAudio`](/slides/python-net/vi/aspose.slides/iaudio) | Một thể hiện [`IAudio`](/slides/python-net/vi/aspose.slides/iaudio) từ bộ sưu tập Presentation.Audios để nhúng. |



### Xem thêm
* lớp [`IAudio`](/slides/python-net/vi/aspose.slides/iaudio)
* lớp [`IAudioFrame`](/slides/python-net/vi/aspose.slides/iaudioframe)
* lớp [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)