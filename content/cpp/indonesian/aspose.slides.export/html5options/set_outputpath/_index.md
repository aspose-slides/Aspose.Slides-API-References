---
title: set_OutputPath()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan di mana sumber daya eksternal harus disimpan. Tulis System::String."
type: docs
weight: 92
url: /id/aspose.slides.export/html5options/set_outputpath/
---
## Html5Options::set_OutputPath(System::String) metode


Menentukan di mana sumber daya eksternal harus disimpan. Tulis [System::String](../../../system/string/).

```cpp
void Aspise::Slides::Export::Html5Options::set_OutputPath(System::String value) override
```

## Keterangan


Contoh:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [Html5Options](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Pustaka [Aspose.Slides](../../../)