---
title: MathBlock()
second_title: Aspose.Slides untuk Referensi API C++
description: Menginisialisasi sebuah instance baru dari kelas MathBlock.
type: docs
weight: 66
url: /id/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() konstruktor


Menginisialisasi sebuah instance baru dari kelas [MathBlock](../).

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## Catatan


Contoh: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) konstruktor


Membuat sebuah blok matematika baru dan menempatkan elemen yang ditentukan di dalamnya

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemen matematika yang akan ditempatkan dalam blok |
## Catatan



Contoh: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) konstruktor


Membuat sebuah blok matematika baru dan menempatkan elemen-elemen yang ditentukan di dalamnya

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | Elemen-elemen matematika yang akan ditempatkan dalam blok |
## Catatan



Contoh: 
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [MathBlock](../)
* Kelas [IMathElement](../../imathelement/)
* Kelas [IEnumerable](../../../system.collections.generic/ienumerable/)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)