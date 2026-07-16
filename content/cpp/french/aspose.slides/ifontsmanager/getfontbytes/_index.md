---
title: GetFontBytes()
second_title: Référence de l'API Aspose.Slides pour C++
description: Récupère le tableau d'octets représentant les données de police pour un style de police et des données de police spécifiés.
type: docs
weight: 131
url: /fr/aspose.slides/ifontsmanager/getfontbytes/
---
## IFontsManager::GetFontBytes(System::SharedPtr\<IFontData\>, FontStyleType) method


Récupère le tableau d'octets représentant les données de police pour un style de police et des données de police spécifiés.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IFontsManager::GetFontBytes(System::SharedPtr<IFontData> fontData, FontStyleType fontStyle)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | L'objet de données de police contenant les informations sur la police [IFontData](../../ifontdata/). |
| fontStyle | [FontStyleType](../../fontstyletype/) | Le style de la police dont les données doivent être récupérées [FontStyleType](../../fontstyletype/). |

### Valeur de retour

Un tableau d'octets contenant les données de police pour le style de police spécifié. Si les données de police ou le style ne sont pas trouvés, renvoie null.

## Remarques




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## Voir aussi

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)