---
title: group method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.mathtext/mathmatrix/group/
weight: 110
---
## group(self) {#}
Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah

### Returns

Instansi baru dari tipe [`IMathGroupingCharacter`](/slides/python-net/id/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Menempatkan elemen ini dalam grup menggunakan karakter pengelompokkan seperti kurung kurawal bawah atau karakter lain

### Returns

Instansi baru dari tipe [`IMathGroupingCharacter`](/slides/python-net/id/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| character | **char** | Karakter Pengelompokkan seperti BOTTOM CURLY BRACKET (U+23DF) atau lainnya |
| position | [`MathTopBotPositions`](/slides/python-net/id/aspose.slides.mathtext/mathtopbotpositions) | Posisi karakter pengelompokkan |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/id/aspose.slides.mathtext/mathtopbotpositions) | Justifikasi vertikal karakter grup.<br/><br/>            Menentukan perataan objek relatif terhadap garis dasar.<br/><br/>            Sebagai contoh, ketika karakter grup berada di atas objek, <br/><br/>            VerticalJustification of Top menunjukkan bahwa bagian atas objek berada pada garis dasar;<br/><br/>            ketika VerticalJustification diatur ke Bottom, bagian bawah objek berada pada garis dasar |

### Lihat Juga
* kelas [`IMathGroupingCharacter`](/slides/python-net/id/aspose.slides.mathtext/imathgroupingcharacter)
* kelas [`MathMatrix`](/slides/python-net/id/aspose.slides.mathtext/mathmatrix)
* enumerasi [`MathTopBotPositions`](/slides/python-net/id/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/id/aspose.slides.mathtext)
* perpustakaan [`Aspose.Slides`](/slides/python-net)