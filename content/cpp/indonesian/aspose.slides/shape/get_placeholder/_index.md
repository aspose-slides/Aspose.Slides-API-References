---
title: get_Placeholder()
second_title: Aspose.Slides untuk C++ Referensi API
description: Mengembalikan placeholder untuk sebuah bentuk. Mengembalikan null jika bentuk tidak memiliki placeholder. Hanya-baca IPlaceholder.
type: docs
weight: 14
url: /id/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() metode

Mengembalikan placeholder untuk shape. Mengembalikan null jika shape tidak memiliki placeholder. Hanya-baca [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## Keterangan

Contoh berikut menunjukkan cara mengubah Text di [Placeholder](../../placeholder/).
```cpp
// Membuat instance kelas Presentation
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// Mengakses slide pertama
auto slide = pres->get_Slides()->idx_get(0);

// Mengiterasi shape untuk menemukan placeholder
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // Mengubah teks pada setiap placeholder
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// Menyimpan presentasi ke disk
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
 Contoh berikut menunjukkan cara menetapkan Prompt Text di [Placeholder](../../placeholder/).
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation2.pptx");

auto slide = pres->get_Slides()->idx_get(0);
for (auto&& shape : slide->get_Slide()->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr && System::ObjectExt::Is<AutoShape>(shape))
    {
        System::String text = u"";
        if (shape->get_Placeholder()->get_Type() == PlaceholderType::CenteredTitle)
        {
            text = u"Add Title";
        }
        else if (shape->get_Placeholder()->get_Type() == PlaceholderType::Subtitle)
        {
            text = u"Add Subtitle";
        }

        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(text);

        System::Console::WriteLine(System::String::Format(u"Placeholder with text: {0}", text));
    }
}

pres->Save(u"Placeholders_PromptText.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IPlaceholder](../../iplaceholder/)
* Kelas [Shape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)