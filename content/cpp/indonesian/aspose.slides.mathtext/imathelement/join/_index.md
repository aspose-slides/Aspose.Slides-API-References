---
title: Join()
second_title: Referensi API Aspose.Slides untuk C++
description: Menggabungkan elemen matematika dan membentuk blok matematika
type: docs
weight: 14
url: /id/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) metode


Menggabungkan elemen matematika dan membentuk blok matematika

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Elemen yang akan digabungkan |

### Nilai Kembalian

Sebuah [IMathBlock](../../imathblock/) baru yang berisi instance ini dan argumen yang ditentukan
## Keterangan



Contoh: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) metode


Menggabungkan teks matematika dan membentuk blok matematika

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Teks matematika yang akan digabungkan |

### Nilai Kembalian

Sebuah [IMathBlock](../../imathblock/) baru yang berisi instance ini dan argumen yang ditentukan
## Keterangan



Contoh: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathBlock](../../imathblock/)
* Kelas [IMathElement](../)
* Kelas [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)