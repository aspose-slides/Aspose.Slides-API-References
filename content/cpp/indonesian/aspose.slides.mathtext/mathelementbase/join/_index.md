---
title: Join()
second_title: Referensi API Aspose.Slides untuk C++
description: Menggabungkan elemen matematika dan membentuk blok matematika
type: docs
weight: 1
url: /id/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) metode

Menggabungkan elemen matematika dan membentuk blok matematika

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemen yang akan digabungkan |

### Nilai Kembali

Sebuah [IMathBlock](../../imathblock/) baru yang berisi instance ini dan argumen yang ditentukan

## Catatan

Contoh: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) metode

Menggabungkan teks matematika dan membentuk blok matematika

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Teks matematika yang akan digabungkan |

### Nilai Kembali

Sebuah [IMathBlock](../../imathblock/) baru yang berisi instance ini dan argumen yang ditentukan

## Catatan

Contoh: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathBlock](../../imathblock/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathElementBase](../)
* Kelas [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)