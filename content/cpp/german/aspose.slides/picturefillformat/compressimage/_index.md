---
title: CompressImage()
second_title: Aspose.Slides für C++ API-Referenz
description: Komprimiert das Bild, indem es die Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert. Optional werden auch beschnittene Bereiche gelöscht.
type: docs
weight: 443
url: /de/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) Methode


Komprimiert das Bild, indem es die Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert. Optional werden auch beschnittene Bereiche gelöscht.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Wenn true, entfernt die Methode die beschnittenen Bereiche des Bildes, wodurch die Größe weiter reduziert werden kann. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | Die Zielauflösung für die Komprimierung, angegeben als Wert des [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/)-Enums. |

### Rückgabewert

Ein **bool**, das angibt, ob das Bild erfolgreich komprimiert wurde. Gibt ****true**** zurück.

## Anmerkungen


Diese Methode ändert die Größe und Auflösung des Bildes ähnlich der PowerPoint-Funktion „Bildformat → Bilder komprimieren“.

wenn das Bild verkleinert oder beschnitten wurde, sonst ****false****

. 


Das folgende Beispiel zeigt, wie die **CompressImage**-Methode verwendet wird, um die Größe eines Bildes in einer Präsentation zu reduzieren, indem eine Zielauflösung festgelegt und beschnittene Bereiche entfernt werden: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Komprimiert das Bild mit einer Zielauflösung von 150 DPI (Webauflösung) und entfernt beschnittene Bereiche
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) Methode


Komprimiert das Bild, indem es die Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert. Optional werden auch beschnittene Bereiche gelöscht.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Wenn true, entfernt die Methode die beschnittenen Bereiche des Bildes, wodurch die Größe weiter reduziert werden kann. |
| resolution | **float** | Die Zielauflösung in DPI. Dieser Wert muss positiv sein und definiert, wie das Bild skaliert wird. |

### Rückgabewert

Ein **bool**, das angibt, ob das Bild erfolgreich komprimiert wurde. Gibt ****true**** zurück.

## Anmerkungen


Diese Methode ändert die Größe und Auflösung des Bildes ähnlich der PowerPoint-Funktion „Bildformat → Bilder komprimieren“.

wenn das Bild verkleinert oder beschnitten wurde, sonst ****false****

. 


Das folgende Beispiel zeigt, wie die **CompressImage**-Methode verwendet wird, um die Größe eines Bildes in einer Präsentation zu reduzieren, indem eine Zielauflösung festgelegt und beschnittene Bereiche entfernt werden: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Holt das PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Komprimiert das Bild mit einer Zielauflösung von 150 DPI (Webauflösung) und entfernt beschnittene Bereiche
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Webauflösung
```

## Siehe auch

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)