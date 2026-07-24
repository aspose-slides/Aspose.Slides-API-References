---
title: get_InkEffectImages()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die Sammlung benutzerdefinierter Bilder, die verwendet werden, um visuelle Effekte für Tintenpinsel zu simulieren. Diese Bilder werden beim Rendern von Tinte mit bestimmten InkEffectType-Werten verwendet, z. B. Galaxy, Rainbow usw. Durch das Bereitstellen Ihrer eigenen Bilder können Sie steuern, wie jeder Tinteneffekt angezeigt wird.
type: docs
weight: 14
url: /de/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() Methode


Ermittelt die Sammlung benutzerdefinierter Bilder, die verwendet werden, um visuelle Effekte für Tintenpinsel zu simulieren. Diese Bilder werden beim Rendern von Tinte mit bestimmten [InkEffectType](../../inkeffecttype/)-Werten verwendet, z. B. Galaxy, Rainbow usw. Durch das Bereitstellen Ihrer eigenen Bilder können Sie steuern, wie jeder Tinteneffekt angezeigt wird.

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## Anmerkungen


Diese Eigenschaft ermöglicht das Ersetzen der Standard-Texturen für Tinteneffekte durch benutzerdefinierte, was besonders nützlich ist, wenn Standard-Assets durch Lizenzbeschränkungen eingeschränkt oder zur Laufzeit nicht verfügbar sind.

Jeder Eintrag im Wörterbuch muss einen [InkEffectType](../../inkeffecttype/)-Wert mit einem entsprechenden [IImage](../../../aspose.slides/iimage/)-Objekt verknüpfen (z. B. Bitmap oder eine **Aspose**-Bildschnittstelle).

```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## Siehe auch

* Aufzählung [InkEffectType](../../inkeffecttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDictionary](../../../system.collections.generic/idictionary/)
* Klasse [IImage](../../../aspose.slides/iimage/)
* Klasse [Ink](../)
* Namensraum [Aspose::Slides::Ink](../../)
* Bibliothek [Aspose.Slides](../../../)