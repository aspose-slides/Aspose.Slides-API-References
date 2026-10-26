---
title: get_OutputPath()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan di mana sumber daya eksternal harus disimpan. Baca System::String."
type: docs
weight: 79
url: /id/aspose.slides.export/html5options/get_outputpath/
---
## Html5Options::get_OutputPath() metode

Menentukan di mana sumber daya eksternal harus disimpan. Baca [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::Html5Options::get_OutputPath() override
```

## Catatan

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