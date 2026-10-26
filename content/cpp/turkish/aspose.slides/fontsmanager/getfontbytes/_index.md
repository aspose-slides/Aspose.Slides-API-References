---
title: GetFontBytes()
second_title: C++ için Aspose.Slides API Referansı
description: Belirli bir yazı tipi stili ve yazı tipi verisi için yazı tipi verisini temsil eden bayt dizisini alır.
type: docs
weight: 131
url: /tr/aspose.slides/fontsmanager/getfontbytes/
---
## FontsManager::GetFontBytes(System::SharedPtr\<Aspose::Slides::IFontData\>, Aspose::Slides::FontStyleType) metod


Belirli bir yazı tipi stili ve yazı tipi verisi için yazı tipi verisini temsil eden bayt dizisini alır.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::FontsManager::GetFontBytes(System::SharedPtr<Aspose::Slides::IFontData> fontData, Aspose::Slides::FontStyleType fontStyle) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | [IFontData](../../ifontdata/) hakkında bilgileri içeren yazı tipi veri nesnesi. |
| fontStyle | [Aspose::Slides::FontStyleType](../../fontstyletype/) | Verinin alınacağı yazı tipi stil [FontStyleType](../../fontstyletype/). |

### Dönüş Değeri

Belirtilen yazı tipi stili için yazı tipi verisini içeren bir bayt dizisi. Yazı tipi verisi veya stil bulunamazsa, null döndürür.
## Açıklamalar




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## İlgili

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)