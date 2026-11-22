---
title: FontsManager class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/fontsmanager/
---
## FontsManager kelas

Mengelola font di seluruh presentasi.

Tipe FontsManager mengekspos anggota-anggota berikut:

## Properti

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/id/aspose.slides/fontsmanager/font_subst_rule_list/) | Pengganti font yang digunakan saat merender.<br/>            Baca/tulis [`IFontSubstRuleCollection`](/slides/python-net/id/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/id/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Mewakili kumpulan aturan FontFallBack milik pengguna untuk mengelola koleksi font agar penggantian yang tepat via fungsi fallback<br/>            Baca/tulis [`IFontFallBackRulesCollection`](/slides/python-net/id/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/id/aspose.slides/fontsmanager/prefer_registered_fonts_over_embedded/) | Menentukan apakah font terdaftar harus diprioritaskan dibandingkan font tertanam dengan nama dan gaya font yang sama.<br/>            Ketika diaktifkan, font tertanam yang cocok akan sementara diganti dengan font terdaftar yang bersesuaian selama proses ekspor. |

## Metode

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/id/aspose.slides/fontsmanager/get_substitutions/#) | Mendapatkan informasi tentang font yang akan diganti saat rendering presentasi. |
| [`get_substitutions(self, slides)`](/slides/python-net/id/aspose.slides/fontsmanager/get_substitutions/#listint) | Mendapatkan informasi tentang font yang akan diganti selama rendering slide yang ditentukan. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/id/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Menambahkan font tertanam<br/>            Perlu diingat saat menyalin font apa pun bahwa kebanyakan font memiliki hak cipta. Pertama temukan lisensi sebuah font terlebih dahulu dan verifikasi bahwa mereka dapat dipindahkan secara bebas ke mesin lain. ArgumentException dapat dilemparkan jika data font None atau font ini sudah tertanam. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/id/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Menambahkan font tertanam<br/>            Perlu diingat saat menyalin font apa pun bahwa kebanyakan font memiliki hak cipta. Pertama temukan lisensi sebuah font terlebih dahulu dan verifikasi bahwa mereka dapat dipindahkan secara bebas ke mesin lain. ArgumentException dapat dilemparkan jika data font None atau font ini sudah tertanam. |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/id/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Ganti font dalam presentasi |
| [`replace_font(self, subst_rule)`](/slides/python-net/id/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Ganti font dalam presentasi menggunakan informasi yang diberikan dalam [`FontSubstRule`](/slides/python-net/id/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/id/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Ganti font dalam presentasi menggunakan informasi yang diberikan dalam koleksi [`FontSubstRule`](/slides/python-net/id/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/id/aspose.slides/fontsmanager/get_fonts/#) | Mengembalikan font yang digunakan dalam presentasi |
| [`get_embedded_fonts(self)`](/slides/python-net/id/aspose.slides/fontsmanager/get_embedded_fonts/#) | Mengembalikan font yang tertanam dalam presentasi |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/id/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Menghapus font yang tertanam |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/id/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Mengambil array byte yang mewakili data font untuk gaya font dan data font tertentu. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/id/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Menentukan tingkat embedding sebuah font dari array byte dan nama font yang diberikan. |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)