---
title: get_NoBreak()
second_title: Referensi API Aspose.Slides untuk C++
description: "Tidak ada jeda. Properti ini menentukan properti \"unbreakable\" pada kotak objek. Ketika bernilai true, tidak ada pemisahan baris yang dapat terjadi di dalam kotak. Hal ini dapat penting untuk emulator operator yang terdiri dari lebih dari satu operator biner. Ketika elemen ini tidak ditentukan, pemisahan dapat terjadi di dalam kotak. Default: true"
type: docs
weight: 40
url: /id/aspose.slides.mathtext/imathbox/get_nobreak/
---
## IMathBox::get_NoBreak() method


Tidak ada jeda. Properti ini menentukan properti \"unbreakable\" pada kotak objek. Ketika bernilai true, tidak ada pemisahan baris yang dapat terjadi di dalam kotak. Hal ini dapat penting untuk emulator operator yang terdiri dari lebih dari satu operator biner. Ketika elemen ini tidak ditentukan, pemisahan dapat terjadi di dalam kotak. Default: true

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_NoBreak()=0
```

## Remarks


Contoh: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## See Also

* Class [IMathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)