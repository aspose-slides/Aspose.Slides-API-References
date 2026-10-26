---
title: group method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/
weight: 80
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
Menempatkan elemen ini dalam grup menggunakan karakter pengelompokan seperti kurung kurawal bawah atau karakter lainnya

### Mengembalikan

Instansi baru dari tipe [`IMathGroupingCharacter`](/slides/python-net/id/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | Karakter Pengelompokan seperti BOTTOM CURLY BRACKET (U+23DF) atau karakter lain |
| position | [`MathTopBotPositions`](/slides/python-net/id/aspose.slides.mathtext/mathtopbotpositions) | Posisi karakter pengelompokan |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/id/aspose.slides.mathtext/mathtopbotpositions) | Vertical justification of group character.<br/><br/>            Specifies the alignment of the object with respect to the baseline.<br/><br/>            For example, when the group character is above the object, <br/><br/>            VerticalJustification of Top signifies that the top of the object falls on the baseline;<br/><br/>            when VerticalJustification is set to Bottom, the bottom of the object is on the baseline |



### Lihat Juga
* kelas [`IMathGroupingCharacter`](/slides/python-net/id/aspose.slides.mathtext/imathgroupingcharacter)
* kelas [`MathRightSubSuperscriptElement`](/slides/python-net/id/aspose.slides.mathtext/mathrightsubsuperscriptelement)
* enumerasi [`MathTopBotPositions`](/slides/python-net/id/aspose.slides.mathtext/mathtopbotpositions)
* modul [`aspose.slides.mathtext`](/slides/python-net/id/aspose.slides.mathtext)
* perpustakaan [`Aspose.Slides`](/slides/python-net)