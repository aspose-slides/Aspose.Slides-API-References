---
title: CreateMathBlock()
second_title: Referensi API Aspose.Slides untuk C++
description: Buat blok matematika
type: docs
weight: 1
url: /id/aspose.slides.mathtext/imathblockfactory/createmathblock/
---
## IMathBlockFactory::CreateMathBlock() metode

Buat blok matematika

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock()=0
```

### Nilai Kembalian

blok matematika baru

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) metode

Buat blok matematika dan letakkan elemen di dalamnya

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Sebuah elemen matematika |

### Nilai Kembalian

blok matematika baru

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) metode

Buat blok matematika dan letakkan elemen-elemen di dalamnya

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | elemen matematika |

### Nilai Kembalian

blok matematika baru

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathBlock](../../imathblock/)
* Kelas [IMathBlockFactory](../)
* Kelas [IMathElement](../../imathelement/)
* Kelas [IMathElementCollection](../../imathelementcollection/)
* Namespace [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)