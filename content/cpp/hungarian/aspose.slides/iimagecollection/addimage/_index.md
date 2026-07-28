---
title: AddImage()
second_title: Aspose.Slides C++ API Referencia
description: Képet ad a prezentációhoz.
type: docs
weight: 14
url: /hu/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) metódus

Képet ad a prezentációhoz.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | A hozzáadandó kép. |

### Visszatérési érték

Hozzáadott kép.

## Megjegyzés

Ez a metódus WMF/EMF meta-fájlokat raszteres PNG képpé konvertál, mielőtt a prezentációba illesztené.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) metódus

Képet ad hozzá egy memóriafolyamból.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Memóriafolyam. |

### Visszatérési érték

Hozzáadott kép.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) metódus

Képet ad a prezentációhoz egy folyamatról.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A képet tartalmazó folyam. |

### Visszatérési érték

Hozzáadott kép.

## Megjegyzés

Ez a metódus WMF/EMF meta-fájlokat adhat hozzá egy prezentációhoz anélkül, hogy raszteres PNG képpé konvertálná őket.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metódus

Létrehoz egy képet és hozzáadja a prezentációhoz egy folyamatról.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A kép fájlt tartalmazó folyam. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | A folyamra alkalmazandó viselkedés. |

### Visszatérési érték

Hozzáadott [IPPImage](../../ippimage/).

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) metódus

Képet ad a prezentációhoz egy megadott pufferből.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Puffer. |

### Visszatérési érték

Hozzáadott kép.

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) metódus

Kép egy másik prezentációból származó másolatát adja hozzá.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Forráskép. |

### Visszatérési érték

Hozzáadott kép.

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) metódus

Képet ad a prezentációhoz egy SVG objektumból.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | SVG kép objektum [ISvgImage](../../isvgimage/) |

### Visszatérési érték

Hozzáadott kép.

## Lásd még

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [IPPImage](../../ippimage/)
* Osztály [IImage](../../iimage/)
* Osztály [IImageCollection](../)
* Osztály [MemoryStream](../../../system.io/memorystream/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [ISvgImage](../../isvgimage/)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)