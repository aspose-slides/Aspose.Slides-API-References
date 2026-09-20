---
title: add_embedded_font method
second_title: Referensi API Aspose.Slides untuk Python melalui .NET
description: 
type: docs
url: /id/aspose.slides/ifontsmanager/add_embedded_font/
weight: 10
---
## add_embedded_font(self, font_data, embed_font_rule) {#ifontdata-asposeslidesexportembedfontcharacters}
Menambahkan font yang disematkan.
            Perlu diingat bahwa ketika menyalin font apa pun, sebagian besar font dilindungi hak cipta. Pertama, temukan lisensi font tersebut terlebih dahulu dan pastikan mereka dapat dipindahkan secara bebas ke mesin lain. ArgumentException dapat dilempar jika font_data bernilai None atau font ini sudah disematkan.

```python
def add_embedded_font(self, font_data, embed_font_rule):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| font_data | [`IFontData`](/slides/python-net/id/aspose.slides/ifontdata) | objek data font [`IFontData`](/slides/python-net/id/aspose.slides/ifontdata) |
| embed_font_rule | [`EmbedFontCharacters`](/slides/python-net/id/aspose.slides.export/embedfontcharacters) | Aturan font tersemat [`EmbedFontCharacters`](/slides/python-net/id/aspose.slides.export/embedfontcharacters) |

## add_embedded_font(self, font_data, embed_font_rule) {#bytes-asposeslidesexportembedfontcharacters}
Menambahkan font yang disematkan
            Perlu diingat ketika menambahkan font apa pun bahwa sebagian besar font dilindungi hak cipta. Pertama, temukan lisensi font tersebut terlebih dahulu dan pastikan mereka dapat dipindahkan secara bebas ke mesin lain. ArgumentException dapat dilempar jika font_data bernilai None atau font ini sudah disematkan.

```python
def add_embedded_font(self, font_data, embed_font_rule):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| font_data | **bytes** | Data font **int**[] |
| embed_font_rule | [`EmbedFontCharacters`](/slides/python-net/id/aspose.slides.export/embedfontcharacters) | Aturan font tersemat [`EmbedFontCharacters`](/slides/python-net/id/aspose.slides.export/embedfontcharacters) |

### See Also
* enumerasi [`EmbedFontCharacters`](/slides/python-net/id/aspose.slides.export/embedfontcharacters)
* kelas [`IFontData`](/slides/python-net/id/aspose.slides/ifontdata)
* kelas [`IFontsManager`](/slides/python-net/id/aspose.slides/ifontsmanager)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)