---
title: group method
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides.mathtext/mathelementbase/group/
weight: 70
---
## group(self) {#}
Menempatkan elemen ini dalam grup menggunakan kurung kurawal bawah

### Mengembalikan

Instansi baru dari tipe [`IMathGroupingCharacter`](/slides/python-net/id/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Menempatkan elemen ini dalam grup menggunakan karakter pengelompokan seperti kurung kurawal bawah atau yang lain

### Mengembalikan

Instansi baru dari tipe [`IMathGroupingCharacter`](/slides/python-net/id/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| character | **char** | Karakter Pengelompokan seperti BOTTOM CURLY BRACKET (U+23DF) atau karakter lain |
| position | [`MathTopBotPositions`](/slides/python-net/id/aspose.slides.mathtext/mathtopbotpositions) | Posisi karakter pengelompokan |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/id/aspose.slides.mathtext/mathtopbotpositions) | Justifikasi vertikal karakter grup.<br/><br/>            Menentukan perataan objek relatif terhadap garis dasar.<br/><br/>            Misalnya, ketika karakter grup berada di atas objek, <br/><br/>            VerticalJustification of Top signifies that the top of the object falls on the baseline;<br/><br/>            ketika VerticalJustification diatur ke Bottom, bagian bawah objek berada pada garis dasar |



### Lihat Juga
* kelas [`IMathGroupingCharacter`](/slides/python-net/id/aspose.slides.mathtext/imathgroupingcharacter)
* kelas [`MathElementBase`](/slides/python-net/id/aspose.slides.mathtext/mathelementbase)
* enumerasi [`MathTopBotPositions`](/slides/python-net/id/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/id/aspose.slides.mathtext)
* perpustakaan [`Aspose.Slides`](/slides/python-net)