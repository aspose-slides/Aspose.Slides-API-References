---
title: MathAccent()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat aksen matematika yang diterapkan pada elemen matematika tertentu dengan nilai karakter aksen default
type: docs
weight: 40
url: /id/aspose.slides.mathtext/mathaccent/mathaccent/
---
## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>) konstruktor

Membuat aksen matematika yang diterapkan pada elemen matematika tertentu dengan nilai karakter aksen default

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemen matematika untuk menerapkan aksen |
## Catatan

Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement);
```

## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>, char16_t) konstruktor

Membuat aksen matematika yang diterapkan pada elemen matematika tertentu

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemen matematika untuk menerapkan aksen |
| accentCharacter | char16_t | karakter aksen |
## Catatan

Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement, u'~');
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathAccent](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)