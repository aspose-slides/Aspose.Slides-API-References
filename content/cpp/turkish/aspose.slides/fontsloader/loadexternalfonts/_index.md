---
title: LoadExternalFonts()
second_title: Aspose.Slides for C++ API Referansı
description: Fontları bulmak için ek klasörler ekler.
type: docs
weight: 1
url: /tr/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) metodu

Fontları bulmak için ek klasörler ekler.

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Ek fontları okumak için dizinler. |

## Açıklamalar

Aşağıdaki örnekler .TTF dosyalarından özel fontların nasıl yükleneceğini gösterir.
```cpp
// Belgeler dizinine giden yol.
System::String dataDir = u"C:\\";

// fontları aramak için klasörler
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// Özel font dizini fontlarını yükle
FontsLoader::LoadExternalFonts(folders);

// Biraz iş yap ve sunum/slayt işleme gerçekleştir
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// Font önbelleğini temizle
FontsLoader::ClearCache();
```

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [FontsLoader](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)