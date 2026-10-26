---
title: Bitmap()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo oggetto Bitmap dall'immagine esistente specificata.
type: docs
weight: 1
url: /it/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) costruttore


Costruisce un nuovo oggetto [Bitmap](../) dall'immagine esistente specificata.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine esistente da cui creare l'immagine bitmap |

## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) costruttore


Costruisce un nuovo oggetto [Bitmap](../) dallo stream specificato.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Uno stream che contiene dati immagine |
| useIcm | **bool** | IGNORATO |

## Bitmap::Bitmap(const String\&) costruttore


Costruisce un nuovo oggetto [Bitmap](../) dal file specificato.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Il nome del file che contiene i dati dell'immagine |

## Bitmap::Bitmap(const String\&, bool) costruttore


Costruisce un nuovo oggetto [Bitmap](../) dal file specificato.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Il nome del file che contiene i dati dell'immagine |
| useIcm | **bool** | IGNORATO |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) costruttore


Costruisce un nuovo oggetto [Bitmap](../) che rappresenta un'immagine bitmap con la larghezza, altezza, formato pixel e dati pixel specificati.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza dell'immagine |
| height | int | L'altezza dell'immagine |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Il formato pixel dell'immagine |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) costruttore


Costruisce un nuovo oggetto [Bitmap](../) dall'immagine esistente specificata, ridimensionata alla dimensione indicata.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine esistente da cui creare l'immagine bitmap |
| size | const [Size](../../size/)\& | La dimensione della nuova immagine |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) costruttore


Costruisce un nuovo oggetto [Bitmap](../) dall'immagine esistente specificata con larghezza e altezza ridimensionate ai valori indicati.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine esistente da cui creare l'immagine bitmap |
| width | int | Larghezza della nuova immagine |
| height | int | Altezza della nuova immagine |

## Vedi anche

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Size](../../size/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)