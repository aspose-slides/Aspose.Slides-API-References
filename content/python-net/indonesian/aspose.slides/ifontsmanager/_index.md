---
title: IFontsManager class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ifontsmanager/
---
## IFontsManager kelas

Mengelola font di seluruh presentasi.

Tipe IFontsManager memperlihatkan anggota-anggota berikut:

## Properti

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/id/aspose.slides/ifontsmanager/font_subst_rule_list/) | Penggantian font yang digunakan saat merender<br/>            Baca/tulis [`IFontSubstRuleCollection`](/slides/python-net/id/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/id/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Mewakili kumpulan aturan FontFallBack pengguna untuk mengelola kumpulan font guna penggantian yang tepat melalui fungsi fallback<br/>            Baca/tulis [`IFontFallBackRulesCollection`](/slides/python-net/id/aspose.slides/ifontfallbackrulescollection). |

## Metode

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/id/aspose.slides/ifontsmanager/get_substitutions/#) | Mendapatkan informasi tentang font yang akan diganti pada proses rendering presentasi. |
| [`get_substitutions(self, slides)`](/slides/python-net/id/aspose.slides/ifontsmanager/get_substitutions/#listint) | Mendapatkan informasi tentang font yang akan diganti selama proses rendering slide yang ditentukan. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/id/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Menambahkan font yang disematkan.<br/>            Perlu diingat ketika menyalin font apa pun bahwa sebagian besar font dilindungi hak cipta. Pertama temukan lisensi <br/>            sebuah font terlebih dahulu dan pastikan dapat dipindahkan secara bebas ke mesin lain. ArgumentException dapat dilemparkan jika data font adalah None atau font ini sudah disematkan |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/id/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Menambahkan font yang disematkan<br/>            Perlu diingat ketika menambahkan font apa pun bahwa sebagian besar font dilindungi hak cipta. Pertama temukan lisensi <br/>            sebuah font terlebih dahulu dan pastikan dapat dipindahkan secara bebas ke mesin lain. ArgumentException dapat dilemparkan jika data font adalah None atau font ini sudah disematkan |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/id/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Ganti font dalam presentasi |
| [`replace_font(self, subst_rule)`](/slides/python-net/id/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Ganti font dalam presentasi menggunakan informasi yang disediakan dalam [`IFontSubstRule`](/slides/python-net/id/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/id/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Ganti font dalam presentasi menggunakan informasi yang disediakan dalam koleksi [`IFontSubstRule`](/slides/python-net/id/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/id/aspose.slides/ifontsmanager/get_fonts/#) | Mengembalikan font yang digunakan dalam presentasi |
| [`get_embedded_fonts(self)`](/slides/python-net/id/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Mengembalikan font yang disematkan dalam presentasi |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/id/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Menghapus font yang disematkan |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/id/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Mendapatkan array byte yang mewakili data font untuk gaya font dan data font tertentu. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/id/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Menentukan tingkat penyematan font dari array byte dan nama font yang diberikan. |


### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)