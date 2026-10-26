---
title: Save()
second_title: Aspose.Slides C++ API referencia
description: Ment minden diát egy prezentációból egy fájlba a megadott formátummal.
type: docs
weight: 404
url: /hu/aspose.slides/ipresentation/save/
---
## IPresentation::Save(System::String, Export::SaveFormat) módszer


Ment minden diát egy prezentációból egy fájlba a megadott formátummal.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Az elkészített fájl elérési útja. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Az exportált adatok formátuma. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) módszer


Ment minden diát egy prezentációból egy folyamba a megadott formátummal.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Kimeneti folyam. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Az exportált adatok formátuma. |

## IPresentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) módszer


Ment minden diát egy prezentációból egy fájlba a megadott formátummal és további beállításokkal.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Az elkészített fájl elérési útja. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Az exportált adatok formátuma. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | További formátumbeállítások. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) módszer


Ment minden diát egy prezentációból egy folyamba a megadott formátummal és további beállításokkal.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Kimeneti folyam. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Az exportált adatok formátuma. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | További formátumbeállítások. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat) módszer


Ment megadott diákat egy prezentációból egy fájlba a megadott formátummal.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Az elkészített fájl elérési útja. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Az diáktételek tömbje, 1-től kezdődően. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Az exportált adatok formátuma. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) módszer


Ment megadott diákat egy prezentációból egy fájlba a megadott formátummal.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Az elkészített fájl elérési útja. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Az diáktételek tömbje, 1-től kezdődően. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Az exportált adatok formátuma. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | További formátumbeállítások. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat) módszer


Ment megadott diákat egy prezentációból egy folyamba a megadott formátummal.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Kimeneti folyam. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Az diáktételek tömbje, 1-től kezdődően. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Az exportált adatok formátuma. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) módszer


Ment megadott diákat egy prezentációból egy folyamba a megadott formátummal és további beállításokkal.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Kimeneti folyam. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Az diáktételek tömbje, 1-től kezdődően. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Az exportált adatok formátuma. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | További formátumbeállítások. |

## IPresentation::Save(System::SharedPtr\<Export::Xaml::IXamlOptions\>) módszer


Ment minden diát egy prezentációból XAML jelölőnyelvet ábrázoló fájlok halmazába.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<Export::Xaml::IXamlOptions> options)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\> | Az XAML formátum beállításai. |
## Megjegyzések



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Lásd még

* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [IPresentation](../)
* Class [Stream](../../../system.io/stream/)
* Class [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Class [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)