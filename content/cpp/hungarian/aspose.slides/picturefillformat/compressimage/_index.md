---
title: CompressImage()
second_title: Aspose.Slides C++ API referencia
description: A képet a méret csökkentésével tömöríti, a forma mérete és a megadott felbontás alapján. Opcióként a levágott területeket is törli.
type: docs
weight: 443
url: /hu/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) metódus


Tömöríti a képet a méret csökkentésével a alakzat mérete és a megadott felbontás alapján. Opcionálisan a levágott területeket is törli.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Ha igaz, a metódus eltávolítja a képről a levágott területeket, ami további méretcsökkentést eredményezhet. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | A tömörítés célfelbontása, amely a [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) felsorolt típus egyik értékeként van megadva. |

### Visszatérési érték

Egy **bool**, amely azt jelzi, hogy a kép sikeresen tömörítve lett-e. Visszatérési érték ****true****

## Megjegyzés


Ez a metódus megváltoztatja a kép méretét és felbontását, ugyanúgy, mint a PowerPoint „Picture Format -> Compress Pictures” funkciója.


ha a képet átméretezték vagy levágták, egyébként ****false****

. 


A következő példa bemutatja, hogyan használható a **CompressImage** metódus egy kép méretének csökkentésére egy prezentációban a célfelbontás beállításával és a levágott területek eltávolításával: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// A képet 150 DPI (web felbontás) célfelbontással tömöríti, és eltávolítja a levágott területeket
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) metódus


Tömöríti a képet a méret csökkentésével a alakzat mérete és a megadott felbontás alapján. Opcionálisan a levágott területeket is törli.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Ha igaz, a metódus eltávolítja a képről a levágott területeket, ami további méretcsökkentést eredményezhet. |
| resolution | **float** | A célfelbontás DPI-ben. Ennek az értéknek pozitívnak kell lennie, és meghatározza, hogyan lesz a kép átméretezve. |

### Visszatérési érték

Egy **bool**, amely azt jelzi, hogy a kép sikeresen tömörítve lett-e. Visszatérési érték ****true****

## Megjegyzés


Ez a metódus megváltoztatja a kép méretét és felbontását, ugyanúgy, mint a PowerPoint „Picture Format -> Compress Pictures” funkciója.


ha a képet átméretezték vagy levágták, egyébként ****false****

. 


A következő példa bemutatja, hogyan használható a **CompressImage** metódus egy kép méretének csökkentésére egy prezentációban a célfelbontás beállításával és a levágott területek eltávolításával: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri a PictureFrame-et
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Tömöríti a képet 150 DPI célfelbontással (Web felbontás) és eltávolítja a levágott területeket
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Web felbontás
```

## Lásd még

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Osztály [PictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)