---
title: AddImage()
second_title: Aspose.Slides C++ API referencia
description: Egy másik prezentációból egy kép másolatát adja hozzá.
type: docs
weight: 53
url: /hu/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) method

Egy képet másol egy másik prezentációból.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Forráskép. |

### Visszatérési érték

Hozzáadott kép.

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) method

Képet ad egy prezentációhoz.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Hozzáadandó kép. |

### Visszatérési érték

Hozzáadott kép.

## Megjegyzés

Ez a metódus WMF/EMF metafájlokat raszteres PNG képpé konvertál, mielőtt a prezentációba illeszti őket.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) method

Képet ad egy prezentációhoz adatfolyamból.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Adatfolyam, amelyből a képet hozzáadja. |

### Visszatérési érték

Hozzáadott kép.

## Megjegyzés

Ez a metódus WMF/EMF metafájlokat képes hozzáadni a prezentációhoz anélkül, hogy raszteres PNG képpé konvertálná őket.

## ImageCollection::AddImage(System::IO::Stream) method

Képet ad egy prezentációhoz adatfolyamból.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Adatfolyam, amelyből a képet hozzáadja. |

### Visszatérési érték

Hozzáadott kép.

## Megjegyzés

Ez a metódus WMF/EMF metafájlokat képes hozzáadni a prezentációhoz anélkül, hogy raszteres PNG képpé konvertálná őket.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) method

Létrehozza és hozzáad egy képet egy prezentációhoz adatfolyamból.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Adatfolyam, amelyből a képfájlt hozzáadja. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | A viselkedés, amelyet az adatfolyamra alkalmaznak. |

### Visszatérési érték

Hozzáadott [IPPImage](../../ippimage/).

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) method

Képet ad egy prezentációhoz a megadott pufforból.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Puffer. |

### Visszatérési érték

Hozzáadott kép.

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) method

Képet ad egy prezentációhoz SVG objektumból.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Svg kép objektum [ISvgImage](../../isvgimage/) |

### Visszatérési érték

Hozzáadott kép.

## Lásd még

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [ImageCollection](../)
* Class [IImage](../../iimage/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)