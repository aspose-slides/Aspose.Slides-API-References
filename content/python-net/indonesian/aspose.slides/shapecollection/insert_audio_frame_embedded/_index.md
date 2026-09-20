---
title: insert_audio_frame_embedded method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/shapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Membuat bingkai audio baru dengan file WAV tersemat dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. Audio yang tersemat ditambahkan ke koleksi Presentation.Audios.

### Mengembalikan

[`IAudioFrame`](/slides/python-net/id/aspose.slides/iaudioframe) yang baru dibuat.



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol tempat menyisipkan bingkai audio. |
| x | **float** | Koordinat x bingkai audio baru, dalam poin. |
| y | **float** | Koordinat y bingkai audio baru, dalam poin. |
| width | **float** | Lebar bingkai audio baru, dalam poin. |
| height | **float** | Tinggi bingkai audio baru, dalam poin. |
| audio_stream | **io.RawIOBase** | Aliran input yang berisi data audio WAV untuk disematkan. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Membuat bingkai audio baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan menggunakan objek audio yang ada dari daftar Presentation.Audios.

### Mengembalikan

[`IAudioFrame`](/slides/python-net/id/aspose.slides/iaudioframe) yang baru dibuat.



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol tempat menyisipkan bingkai audio. |
| x | **float** | Koordinat x bingkai audio baru, dalam poin. |
| y | **float** | Koordinat y bingkai audio baru, dalam poin. |
| width | **float** | Lebar bingkai audio baru, dalam poin. |
| height | **float** | Tinggi bingkai audio baru, dalam poin. |
| audio | [`IAudio`](/slides/python-net/id/aspose.slides/iaudio) | Sebuah instance [`IAudio`](/slides/python-net/id/aspose.slides/iaudio) dari koleksi Presentation.Audios untuk disematkan. |



### Lihat Juga
* kelas [`IAudio`](/slides/python-net/id/aspose.slides/iaudio)
* kelas [`IAudioFrame`](/slides/python-net/id/aspose.slides/iaudioframe)
* kelas [`ShapeCollection`](/slides/python-net/id/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)