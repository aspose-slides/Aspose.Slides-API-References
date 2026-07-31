---
title: MathematicalText()
second_title: Referensi API Aspose.Slides untuk C++
description: "Konstruktor default (buat String::Empty Value)"
type: docs
weight: 40
url: /id/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() konstruktor

Konstruktor default (buat String::Empty Value)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## Catatan

Contoh: 
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) konstruktor

Buat [MathText](../../) dengan simbol tunggal

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathSymbol | char16_t | simbol tunggal |
## Catatan

Contoh: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) konstruktor

Buat [MathematicalText](../) dari teks

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | nilai teks |
## Catatan

Contoh: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) konstruktor

Buat [MathematicalText](../) dari teks dan pengaturan format

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | nilai teks |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | pengaturan format teks |
## Catatan

Contoh: 
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [MathematicalText](../)
* Kelas [String](../../../system/string/)
* Kelas [IPortionFormat](../../../aspose.slides/iportionformat/)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)