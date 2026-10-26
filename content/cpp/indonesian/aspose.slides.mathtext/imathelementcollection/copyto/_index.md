---
title: CopyTo()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyalin ke array yang ditentukan.
type: docs
weight: 118
url: /id/aspose.slides.mathtext/imathelementcollection/copyto/
---
## IMathElementCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IMathElement\>\>, int32_t) method

Salin ke array yang ditentukan.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IMathElement>> array, int32_t arrayIndex)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\> | Array yang akan disalin. |
| arrayIndex | **int32_t** | Indeks untuk memulai penyalinan. |
## Catatan



Contoh: 
```cpp
System::SharedPtr<IMathElementCollection> collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
auto destinationArray = System::MakeArray<System::SharedPtr<IMathElement>>(collection->get_Count());
collection->CopyTo(destinationArray, 0);
```

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [IMathElementCollection](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)