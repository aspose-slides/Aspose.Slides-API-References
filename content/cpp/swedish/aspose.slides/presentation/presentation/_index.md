---
title: Presentation()
second_title: Aspose.Slides för C++ API-referens
description: Denna konstruktor skapar en ny presentation från grunden. Den skapade presentationen har en tom bild.
type: docs
weight: 417
url: /sv/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() konstruktor


Den här konstruktorn skapar en ny presentation från grunden. Den skapade presentationen har en tom bild.

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) konstruktor


Den här konstruktorn skapar en ny presentation från grunden. Den skapade presentationen har en tom bild.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Ytterligare laddningsalternativ. |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) konstruktor


Den här konstruktorn är den primära mekanismen för att läsa en befintlig [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Indataström. |
## Anmärkningar




```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) konstruktor


Den här konstruktorn är den primära mekanismen för att läsa en befintlig [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Indataström. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Ytterligare laddningsalternativ. |

## Presentation::Presentation(System::String) konstruktor


Den här konstruktorn får en sökväg till källfilen varifrån innehållet i [Presentation](../) läses.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Indatafil. |
## Anmärkningar 




```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) konstruktor


Den här konstruktorn får en sökväg till källfilen varifrån innehållet i [Presentation](../) läses.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Indatafil. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Ytterligare laddningsalternativ. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Presentation](../)
* Klass [LoadOptions](../../loadoptions/)
* Klass [Stream](../../../system.io/stream/)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)