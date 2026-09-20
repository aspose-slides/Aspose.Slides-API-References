---
title: enclose method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---
## enclose(self) {#}
Membungkus elemen matematika dalam tanda kurung

### Mengembalikan

Elemen matematika tipe [`IMathDelimiter`](/slides/python-net/id/aspose.slides.mathtext/imathdelimiter) yang mencakup tanda kurung



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Membungkus elemen matematika dengan karakter tertentu seperti tanda kurung atau karakter lain sebagai bingkai

### Mengembalikan

Jika `beginning_character` dan `ending_character` adalah None, 
            properti yang bersangkutan hanya diberikan nilai dan tidak ada objek baru yang dibuat (mengembalikan instance ini).
            Jika tidak, mengembalikan elemen matematika baru bertipe Delimiter yang mencakup karakter yang ditentukan sebagai bingkai 
            dan instance [`MathDelimiter`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter) ini dibingkai di dalamnya.



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| beginning_character | **char** | Karakter awal (biasanya kurung kiri) |
| ending_character | **char** | Karakter akhir (biasanya kurung kanan) |



### Lihat Juga
* kelas [`IMathDelimiter`](/slides/python-net/id/aspose.slides.mathtext/imathdelimiter)
* kelas [`MathDelimiter`](/slides/python-net/id/aspose.slides.mathtext/mathdelimiter)
* modul [`aspose.slides.mathtext`](/slides/python-net/id/aspose.slides.mathtext)
* perpustakaan [`Aspose.Slides`](/slides/python-net)