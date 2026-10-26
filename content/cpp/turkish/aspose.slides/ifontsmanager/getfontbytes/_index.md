---
title: GetFontBytes()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen bir yazı stili ve yazı verisi için yazı verisini temsil eden bayt dizisini alır.
type: docs
weight: 131
url: /tr/aspose.slides/ifontsmanager/getfontbytes/
---
## IFontsManager::GetFontBytes(System::SharedPtr\<IFontData\>, FontStyleType) method

Belirtilen bir yazı stili ve yazı verisi için yazı verisini temsil eden bayt dizisini alır.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IFontsManager::GetFontBytes(System::SharedPtr<IFontData> fontData, FontStyleType fontStyle)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Yazı veri nesnesi, [IFontData](../../ifontdata/) hakkında bilgi içerir. |
| fontStyle | [FontStyleType](../../fontstyletype/) | Verisinin alınacağı yazı stilidir [FontStyleType](../../fontstyletype/). |

### Dönüş Değeri

Belirtilen yazı stili için yazı verisini içeren bir bayt dizisi. Yazı verisi ya da stil bulunamazsa, null döner.

## Notlar

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## İlgili

* Numarlama [FontStyleType](../../fontstyletype/)
* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IFontData](../../ifontdata/)
* Sınıf [IFontsManager](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)