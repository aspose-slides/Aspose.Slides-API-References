---
title: RemoveWriteProtection()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghapus perlindungan penulisan untuk presentasi ini.
type: docs
weight: 144
url: /id/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() metode

Menghapus perlindungan penulisan untuk presentasi ini.

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## Catatan

Kode contoh ini menunjukkan cara menghapus perlindungan penulisan dari PowerPoint [Presentation](../../presentation/).
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [ProtectionManager](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)