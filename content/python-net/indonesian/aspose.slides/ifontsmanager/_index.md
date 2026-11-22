---
title: IFontsManager class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ifontsmanager/
---
## IFontsManager kelas

Mengelola font di seluruh presentasi.

Tipe IFontsManager menampilkan anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/id/aspose.slides/ifontsmanager/font_subst_rule_list/) | Penggantian font yang digunakan saat rendering<br/>            Baca/tulis [`IFontSubstRuleCollection`](/slides/python-net/id/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/id/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Mewakili koleksi aturan FontFallBack milik pengguna untuk mengelola koleksi font demi substitusi yang tepat melalui fungsi fallback<br/>            Baca/tulis [`IFontFallBackRulesCollection`](/slides/python-net/id/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/id/aspose.slides/ifontsmanager/prefer_registered_fonts_over_embedded/) | Menentukan apakah font terdaftar harus diprioritaskan dibandingkan font yang disematkan dengan nama dan gaya font yang sama.<br/>            Saat diaktifkan, font yang disematkan yang cocok akan sementara diganti dengan font terdaftar yang sesuai selama ekspor. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/id/aspose.slides/ifontsmanager/get_substitutions/#) | Mendapatkan informasi tentang font yang akan diganti pada proses rendering presentasi. |
| [`get_substitutions(self, slides)`](/slides/python-net/id/aspose.slides/ifontsmanager/get_substitutions/#listint) | Mendapatkan informasi tentang font yang akan diganti saat rendering slide yang ditentukan. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/id/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Menambahkan font yang disematkan.<br/>            Perlu diingat saat menyalin font apa pun bahwa kebanyakan font dilindungi hak cipta. Pertama, temukan lisensi dari font terlebih dahulu dan verifikasi bahwa font tersebut dapat dipindahkan secara bebas ke mesin lain. ArgumentException dapat dilemparkan jika data font bernilai None atau font ini sudah disematkan |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/id/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Menambahkan font yang disematkan<br/>            Perlu diingat saat menambahkan font apa pun bahwa kebanyakan font dilindungi hak cipta. Pertama, temukan lisensi dari font terlebih dahulu dan verifikasi bahwa font tersebut dapat dipindahkan secara bebas ke mesin lain. ArgumentException dapat dilemparkan jika data font bernilai None atau font ini sudah disematkan |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/id/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Ganti font dalam presentasi |
| [`replace_font(self, subst_rule)`](/slides/python-net/id/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Ganti font dalam presentasi menggunakan informasi yang disediakan dalam [`IFontSubstRule`](/slides/python-net/id/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/id/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Ganti font dalam presentasi menggunakan informasi yang disediakan dalam koleksi [`IFontSubstRule`](/slides/python-net/id/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/id/aspose.slides/ifontsmanager/get_fonts/#) | Mengembalikan font yang digunakan dalam presentasi |
| [`get_embedded_fonts(self)`](/slides/python-net/id/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Mengembalikan font yang disematkan dalam presentasi |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/id/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Menghapus font yang disematkan |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/id/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Mengambil array byte yang mewakili data font untuk gaya font dan data font yang ditentukan. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/id/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Menentukan tingkat penyematan font dari array byte dan nama font yang diberikan. |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)