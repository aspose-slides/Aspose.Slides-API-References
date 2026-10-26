---
title: CompressImage()
second_title: Aspose.Slides pro C++ API referenci
description: Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti.
type: docs
weight: 443
url: /cs/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) metoda


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Pokud je true, metoda odstraní oříznuté oblasti obrázku, což může dále snížit jeho velikost. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | Cílové rozlišení pro kompresi, uvedené jako hodnota výčtu [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/). |

### Návratová hodnota

Bool, který udává, zda byl obrázek úspěšně komprimován. Vrací ****true****

## Poznámky


Tato metoda mění velikost a rozlišení obrázku podobně jako funkce PowerPointu „Picture Format -> Compress Pictures“.

pokud byl obrázek změněn velikost nebo oříznut, jinak ****false****

. 


Následující příklad ukazuje, jak použít metodu **CompressImage** ke snížení velikosti obrázku v prezentaci nastavením cílového rozlišení a odstraněním oříznutých oblastí: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Komprimujte obrázek s cílovým rozlišením 150 DPI (webové rozlišení) a odstraňte oříznuté oblasti
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) metoda


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Pokud je true, metoda odstraní oříznuté oblasti obrázku, což může dále snížit jeho velikost. |
| resolution | **float** | Cílové rozlišení v DPI. Tato hodnota musí být kladná a určuje, jak bude obrázek změněn velikost. |

### Návratová hodnota

Bool, který udává, zda byl obrázek úspěšně komprimován. Vrací ****true****

## Poznámky


Tato metoda mění velikost a rozlišení obrázku podobně jako funkce PowerPointu „Picture Format -> Compress Pictures“.

pokud byl obrázek změněn velikost nebo oříznut, jinak ****false****

. 


Následující příklad ukazuje, jak použít metodu **CompressImage** ke snížení velikosti obrázku v prezentaci nastavením cílového rozlišení a odstraněním oříznutých oblastí: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Komprimujte obrázek s cílovým rozlišením 150 DPI (webové rozlišení) a odstraňte oříznuté oblasti
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Webové rozlišení
```

## Viz také

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)