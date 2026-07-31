---
title: MathPhantom()
second_title: Referensi API Aspose.Slides untuk C++
description: Menginisialisasi sebuah instance baru dari kelas MathPhantom menggunakan elemen matematika dasar yang ditentukan.
type: docs
weight: 144
url: /id/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) konstruktor


Menginisialisasi sebuah instance baru dari kelas [MathPhantom](../) menggunakan elemen matematika dasar yang ditentukan.

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | [IMathElement](../../imathelement/) dasar yang visibilitas dan tata letaknya akan dikendalikan oleh phantom. Elemen ini mendefinisikan konten yang dapat disembunyikan atau ditampilkan, sambil tetap memengaruhi penyelarasan geometris matematika di sekitarnya. |
## Catatan



Elemen phantom digunakan untuk memesan atau menekan ruang visual dari ekspresi dasarnya tanpa harus menampilkannya. Elemen ini bersesuaian dengan elemen OMML **<m:phant>**. 

Contoh: 
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathPhantom](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)