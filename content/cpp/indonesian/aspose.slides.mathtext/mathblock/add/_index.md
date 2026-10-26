---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan elemen matematika ke akhir koleksi.
type: docs
weight: 79
url: /id/aspose.slides.mathtext/mathblock/add/
---
## MathBlock::Add(System::SharedPtr\<IMathElement\>) metode


Menambahkan elemen matematika ke akhir koleksi.

```cpp
void Aspose::Slides::MathText::MathBlock::Add(System::SharedPtr<IMathElement> item) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | [IMathElement](../../imathelement/) yang akan ditambahkan ke akhir koleksi. |
## Catatan



Contoh: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
mathBlock->Add(System::MakeObject<MathematicalText>(u"+"));
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)