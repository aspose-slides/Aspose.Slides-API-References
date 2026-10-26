---
title: get_object_storing_location method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
Menentukan di mana objek harus disimpan.
            Metode ini dipanggil sekali untuk setiap id objek.
            Tidak dijamin tidak akan ada dua objek dengan data, semanticName dan contentType yang sama tetapi dengan id yang berbeda.

### Mengembalikan

Keputusan



```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```



| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| id | **int** | Id objek. Id ini unik untuk seluruh operasi penyimpanan. |
| entity_data | **bytes** | Data biner objek. Parameter ini dapat None, jika data biner objek belum dihasilkan. |
| semantic_name | **str** | Beberapa teks pendek yang menjelaskan makna objek. Kontroler dapat menggunakan ini sebagai bagian dari nama objek eksternal, namun terserah dispatcher untuk memastikan nama-nama tersebut unik dan hanya berisi karakter yang diizinkan. |
| content_type | **str** | Tipe MIME objek. |
| recomended_extension | **str** | Ekstensi nama file, yang direkomendasikan untuk tipe MIME ini. |



### Lihat Juga
* kelas [`ILinkEmbedController`](/slides/python-net/id/aspose.slides.export/ilinkembedcontroller)
* enumerasi [`LinkEmbedDecision`](/slides/python-net/id/aspose.slides.export/linkembeddecision)
* modul [`aspose.slides.export`](/slides/python-net/id/aspose.slides.export)
* pustaka [`Aspose.Slides`](/slides/python-net)