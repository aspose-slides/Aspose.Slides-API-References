---
title: CreateMathBlock()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat blok matematika
type: docs
weight: 1
url: /id/aspose.slides.mathtext/mathblockfactory/createmathblock/
---
## MathBlockFactory::CreateMathBlock() metode

Buat blok matematika

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock() override
```

### Nilai Kembalian

blok matematika baru

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) metode

Buat blok matematika dan letakkan elemen di dalamnya

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement) override
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Sebuah elemen matematika |

### Nilai Kembalian

blok matematika baru

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) metode

Buat blok matematika dan letakkan elemen-elemen di dalamnya

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements) override
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | elemen-elemen matematika |

### Nilai Kembalian

blok matematika baru

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathBlock](../../imathblock/)
* Kelas [MathBlockFactory](../)
* Kelas [IMathElement](../../imathelement/)
* Kelas [IMathElementCollection](../../imathelementcollection/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)