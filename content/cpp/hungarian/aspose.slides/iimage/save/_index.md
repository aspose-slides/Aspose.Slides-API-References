---
title: Save()
second_title: Aspose.Slides C++ API referencia
description: Elmenti a képet egy fájlba.
type: docs
weight: 40
url: /hu/aspose.slides/iimage/save/
---
## IImage::Save(System::String) metódus


Elmenti a képet egy fájlba.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | A fájl elérési útja, ahová a kép mentésre kerül. |


## IImage::Save(System::String, ImageFormat) metódus


A képet a megadott formátumban menti egy fájlba.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | A fájl elérési útja, ahová a kép mentésre kerül. |
| format | [ImageFormat](../../imageformat/) | A kép formátuma. |


## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) metódus


A képet a megadott formátumban egy adatfolyamra menti.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Az adatfolyam, ahová a kép mentésre kerül. |
| format | [ImageFormat](../../imageformat/) | A kép formátuma. |


## IImage::Save(System::String, ImageFormat, int32_t) metódus


A képet a megadott formátumban és minőségben menti egy fájlba.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | A fájl elérési útja, ahová a kép mentésre kerül. |
| format | [ImageFormat](../../imageformat/) | A kép formátuma. |
| quality | **int32_t** | A mentett kép minősége (0-tól 100-ig). 

 Ez a paraméter csak a [ImageFormat::Jpeg](../../imageformat/) mentésére van hatással; minden más formátúnál figyelmen kívül marad. |


## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) metódus


A képet a megadott formátumban és minőségben menti egy adatfolyamra.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Az adatfolyam, ahová a kép mentésre kerül. |
| format | [ImageFormat](../../imageformat/) | A kép formátuma. |
| quality | **int32_t** | A mentett kép minősége (0-tól 100-ig). 

 Ez a paraméter csak a [ImageFormat::Jpeg](../../imageformat/) mentésére van hatással; minden más formátúnál figyelmen kívül marad. |


## Lásd még

* Enum [ImageFormat](../../imageformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [IImage](../)
* Osztály [Stream](../../../system.io/stream/)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)