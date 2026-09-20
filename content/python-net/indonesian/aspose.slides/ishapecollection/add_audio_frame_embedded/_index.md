---
title: add_audio_frame_embedded method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ishapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
Membuat sebuah bingkai audio baru dengan file WAV tersemat dan menambahkannya ke akhir koleksi shape. Audio yang tersemat ditambahkan ke koleksi Presentation.Audios.

### Mengembalikan

[`IAudioFrame`](/slides/python-net/id/aspose.slides/iaudioframe) yang baru dibuat.

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
Membuat sebuah bingkai audio baru dan menambahkannya ke akhir koleksi shape menggunakan objek audio yang ada dari daftar Presentation.Audios.

### Mengembalikan

[`IAudioFrame`](/slides/python-net/id/aspose.slides/iaudioframe) yang baru dibuat.

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
| audio | [`IAudio`](/slides/python-net/id/aspose.slides/iaudio) | Sebuah instance [`IAudio`](/slides/python-net/id/aspose.slides/iaudio) dari koleksi Presentation.Audios. |

### Lihat Juga
* class [`IAudio`](/slides/python-net/id/aspose.slides/iaudio)
* class [`IAudioFrame`](/slides/python-net/id/aspose.slides/iaudioframe)
* class [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)