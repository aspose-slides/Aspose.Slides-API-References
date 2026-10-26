---
title: CompressImage()
second_title: Aspose.Slides C++ API Referencia
description: A képet a forma mérete és a megadott felbontás alapján csökkentve tömöríti. Opcionálisan törli a levágott területeket is.
type: docs
weight: 443
url: /hu/aspose.slides/ipicturefillformat/compressimage/
---
## IPictureFillFormat::CompressImage(bool, Export::PicturesCompression) method

A kép méretét csökkenti a forma mérete és a megadott felbontás alapján. Opcionálisan törli a levágott területeket.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Ha true, a metódus eltávolítja a kép levágott területeit, ami esetleg tovább csökkentheti a méretét. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | A tömörítés célfelbontása, amely a [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) enum egy értékeként van megadva. |

### Visszatérési érték

Egy **bool**, amely azt jelzi, hogy a képet sikeresen tömörítették-e. Returns ****true****

## Megjegyzés

Ez a metódus a kép méretét és felbontását módosítja, hasonlóan a PowerPoint „Picture Format -> Compress Pictures” funkciójához.

ha a képet átméretezték vagy levágták, egyébként ****false****

. 

A következő példa bemutatja, hogyan használható a **CompressImage** metódus egy prezentációban lévő kép méretének csökkentésére célfelbontás megadásával és a levágott területek eltávolításával: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Tömöríti a képet 150 DPI (Web felbontás) célfelbontással és eltávolítja a levágott területeket
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## IPictureFillFormat::CompressImage(bool, float) method

A kép méretét csökkenti a forma mérete és a megadott felbontás alapján. Opcionálisan törli a levágott területeket.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Ha true, a metódus eltávolítja a kép levágott területeit, ami esetleg tovább csökkentheti a méretét. |
| resolution | **float** | A célfelbontás DPI-ben. Ennek az értéknek pozitívnak kell lennie, és meghatározza, hogyan lesz a kép átméretezve. |

### Visszatérési érték

Egy **bool**, amely azt jelzi, hogy a képet sikeresen tömörítették-e. Returns ****true****

## Megjegyzés

Ez a metódus a kép méretét és felbontását módosítja, hasonlóan a PowerPoint „Picture Format -> Compress Pictures” funkciójához.

ha a képet átméretezték vagy levágták, egyébként ****false****

. 

A következő példa bemutatja, hogyan használható a **CompressImage** metódus egy prezentációban lévő kép méretének csökkentésére célfelbontás megadásával és a levágott területek eltávolításával: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri a PictureFrame-et
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Tömöríti a képet 150 DPI (Web felbontás) célfelbontással és eltávolítja a levágott területeket
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Web felbontás
```

## Lásd még

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)