---
title: CompressImage()
second_title: Aspose.Slides für C++ API-Referenz
description: Komprimiert das Bild, indem es seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert. Optional löscht es auch beschnittene Bereiche.
type: docs
weight: 443
url: /de/aspose.slides/ipicturefillformat/compressimage/
---
## IPictureFillFormat::CompressImage(bool, Export::PicturesCompression) Methode

Komprimiert das Bild, indem es seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert. Optional löscht es auch beschnittene Bereiche.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Wenn true, entfernt die Methode die beschnittenen Bereiche des Bildes und reduziert ggf. weiter dessen Größe. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | Die Zielauflösung für die Komprimierung, angegeben als ein Wert des [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) Enums. |

### Rückgabewert

Ein **bool**, das angibt, ob das Bild erfolgreich komprimiert wurde. Gibt ****true**** zurück.

## Hinweise

Diese Methode ändert die Größe und Auflösung des Bildes ähnlich wie die Funktion "Picture Format -> Compress Pictures" in PowerPoint.

wenn das Bild verkleinert oder beschnitten wurde, sonst ****false****.

Das folgende Beispiel zeigt, wie die **CompressImage**-Methode verwendet wird, um die Größe eines Bildes in einer Präsentation zu reduzieren, indem eine Zielauflösung festgelegt und beschnittene Bereiche entfernt werden:
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Komprimiere das Bild mit einer Zielauflösung von 150 DPI (Webauflösung) und entferne beschnittene Bereiche
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## IPictureFillFormat::CompressImage(bool, float) Methode

Komprimiert das Bild, indem es seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert. Optional löscht es auch beschnittene Bereiche.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Wenn true, entfernt die Methode die beschnittenen Bereiche des Bildes und reduziert ggf. weiter dessen Größe. |
| resolution | **float** | Die Zielauflösung in DPI. Dieser Wert muss positiv sein und definiert, wie das Bild skaliert wird. |

### Rückgabewert

Ein **bool**, das angibt, ob das Bild erfolgreich komprimiert wurde. Gibt ****true**** zurück.

## Hinweise

Diese Methode ändert die Größe und Auflösung des Bildes ähnlich wie die Funktion "Picture Format -> Compress Pictures" in PowerPoint.

wenn das Bild verkleinert oder beschnitten wurde, sonst ****false****.

Das folgende Beispiel zeigt, wie die **CompressImage**-Methode verwendet wird, um die Größe eines Bildes in einer Präsentation zu reduzieren, indem eine Zielauflösung festgelegt und beschnittene Bereiche entfernt werden:
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Holt das PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Komprimiere das Bild mit einer Zielauflösung von 150 DPI (Webauflösung) und entferne beschnittene Bereiche
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Webauflösung
```

## Siehe auch

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Klasse [IPictureFillFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)