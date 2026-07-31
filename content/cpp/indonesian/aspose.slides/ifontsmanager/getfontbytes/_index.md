---
title: GetFontBytes()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengambil array byte yang mewakili data font untuk gaya font dan data font yang ditentukan.
type: docs
weight: 131
url: /id/aspose.slides/ifontsmanager/getfontbytes/
---
## IFontsManager::GetFontBytes(System::SharedPtr\<IFontData\>, FontStyleType) metode

Mengambil array byte yang mewakili data font untuk gaya font dan data font yang ditentukan.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IFontsManager::GetFontBytes(System::SharedPtr<IFontData> fontData, FontStyleType fontStyle)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Objek data font yang berisi informasi tentang font [IFontData](../../ifontdata/). |
| fontStyle | [FontStyleType](../../fontstyletype/) | Gaya font yang data-nya akan diambil [FontStyleType](../../fontstyletype/). |

### Nilai Kembalian

Array byte yang berisi data font untuk gaya font yang ditentukan. Jika data font atau gaya tidak ditemukan, mengembalikan null.

## Catatan

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## Lihat Juga

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IFontData](../../ifontdata/)
* Kelas [IFontsManager](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)