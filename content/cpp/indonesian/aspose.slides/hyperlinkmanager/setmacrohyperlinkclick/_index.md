---
title: SetMacroHyperlinkClick()
second_title: Referensi API Aspose.Slides untuk C++
description: Atur tautan makro pada saat klik.
type: docs
weight: 79
url: /id/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager::SetMacroHyperlinkClick(System::String) metode

Mengatur tautan makro pada klik.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetMacroHyperlinkClick(System::String macroName) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Nama makro |

### Nilai Kembali

[Hyperlink](../../hyperlink/) objek [IHyperlink](../../ihyperlink/)

## Catatan

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IHyperlink](../../ihyperlink/)
* Kelas [String](../../../system/string/)
* Kelas [HyperlinkManager](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)