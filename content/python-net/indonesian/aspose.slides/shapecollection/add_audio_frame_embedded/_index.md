---
title: add_audio_frame_embedded method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/shapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
Membuat bingkai audio baru dengan file WAV tersemat dan menambahkannya ke akhir koleksi shape. Audio yang tersemat ditambahkan ke koleksi Presentation.Audios.

### Mengembalikan

[`IAudioFrame`](/slides/python-net/id/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | **float** | Koordinat x dari bingkai audio baru, dalam poin. |
| y | **float** | Koordinat y dari bingkai audio baru, dalam poin. |
| width | **float** | Lebar bingkai audio baru, dalam poin. |
| height | **float** | Tinggi bingkai audio baru, dalam poin. |
| audio_stream | **io.RawIOBase** | Aliran masukan yang berisi data audio WAV untuk disematkan. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
Membuat bingkai audio baru dan menambahkannya ke akhir koleksi shape menggunakan objek audio yang sudah ada dari daftar Presentation.Audios.

### Mengembalikan

[`IAudioFrame`](/slides/python-net/id/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | **float** | Koordinat x dari bingkai audio baru, dalam poin. |
| y | **float** | Koordinat y dari bingkai audio baru, dalam poin. |
| width | **float** | Lebar bingkai audio baru, dalam poin. |
| height | **float** | Tinggi bingkai audio baru, dalam poin. |
| audio | [`IAudio`](/slides/python-net/id/aspose.slides/iaudio) | Instansi [`IAudio`](/slides/python-net/id/aspose.slides/iaudio) dari koleksi Presentation.Audios. |



### Lihat Juga
* kelas [`IAudio`](/slides/python-net/id/aspose.slides/iaudio)
* kelas [`IAudioFrame`](/slides/python-net/id/aspose.slides/iaudioframe)
* kelas [`ShapeCollection`](/slides/python-net/id/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)