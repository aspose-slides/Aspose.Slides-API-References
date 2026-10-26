---
title: SetWriteProtection()
second_title: Referensi API Aspose.Slides untuk C++
description: Atur perlindungan penulisan untuk presentasi ini dengan kata sandi yang ditentukan.
type: docs
weight: 131
url: /id/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) metode

Atur perlindungan penulisan untuk presentasi ini dengan kata sandi yang ditentukan.

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Kata sandi. |
## Catatan

Kode contoh berikut menunjukkan cara mengatur perlindungan penulisan pada presentasi.
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [ProtectionManager](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)