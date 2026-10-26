---
title: Join()
second_title: Referensi API Aspose.Slides untuk C++
description: Menggabungkan elemen matematika dengan blok matematika ini
type: docs
weight: 183
url: /id/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) metode


Menggabungkan elemen matematika dengan blok matematika ini

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemen yang akan digabungkan |

### Nilai Kembalian

Instansi saat ini dari [IMathBlock](../../imathblock/)
## Catatan



Contoh: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) metode


Menggabungkan teks matematika dengan blok matematika ini

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Teks matematika yang akan digabungkan |

### Nilai Kembalian

Sebuah [IMathBlock](../../imathblock/) baru yang berisi instansi ini dan argumen yang ditentukan
## Catatan



Contoh: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathBlock](../../imathblock/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathBlock](../)
* Kelas [String](../../../system/string/)
* Ruang nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)