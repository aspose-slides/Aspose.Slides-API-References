---
title: SetMacroHyperlinkClick()
second_title: Referensi API Aspose.Slides untuk C++
description: Menetapkan tautan makro pada klik.
type: docs
weight: 79
url: /id/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick(System::String) metode

Set tautan makro saat diklik.

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Nama makro |

### Nilai Kembalian

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
* Kelas [IHyperlinkManager](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)