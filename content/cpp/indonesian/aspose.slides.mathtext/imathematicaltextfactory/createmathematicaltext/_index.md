---
title: CreateMathematicalText()
second_title: Referensi API Aspose.Slides untuk C++
description: Buat elemen teks matematis kosong
type: docs
weight: 1
url: /id/aspose.slides.mathtext/imathematicaltextfactory/createmathematicaltext/
---
## IMathematicalTextFactory::CreateMathematicalText() method

Buat elemen Mathematical Text kosong

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText()=0
```

### Nilai Kembalian

baru Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(char16_t) method

Buat elemen Mathematical Text dengan nilai yang ditentukan

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathSymbol | char16_t | simbol tunggal yang digunakan sebagai nilai teks |

### Nilai Kembalian

baru Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String) method

Buat elemen Mathematical Text kosong dengan nilai yang ditentukan

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | nilai teks |

### Nilai Kembalian

baru Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) method

Buat elemen Mathematical Text kosong dengan nilai yang ditentukan dan properti format teks

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | nilai teks |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | pengaturan format teks |

### Nilai Kembalian

baru Mathematical Text

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathematicalText](../../imathematicaltext/)
* Kelas [IMathematicalTextFactory](../)
* Kelas [String](../../../system/string/)
* Kelas [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namespace [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)