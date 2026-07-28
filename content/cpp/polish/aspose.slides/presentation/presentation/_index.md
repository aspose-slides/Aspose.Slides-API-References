---
title: Presentation()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Ten konstruktor tworzy nową prezentację od podstaw. Utworzona prezentacja zawiera jeden pusty slajd.
type: docs
weight: 417
url: /pl/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() konstruktor


Ten konstruktor tworzy nową prezentację od zera. Utworzona prezentacja zawiera jeden pusty slajd.

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) konstruktor


Ten konstruktor tworzy nową prezentację od zera. Utworzona prezentacja zawiera jeden pusty slajd.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Dodatkowe opcje ładowania. |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) konstruktor


Ten konstruktor jest głównym mechanizmem do odczytywania istniejącego [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień wejściowy. |
## Uwagi




```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) konstruktor


Ten konstruktor jest głównym mechanizmem do odczytywania istniejącego [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień wejściowy. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Dodatkowe opcje ładowania. |

## Presentation::Presentation(System::String) konstruktor


Ten konstruktor pobiera ścieżkę do pliku źródłowego, z którego odczytywana jest zawartość [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Plik wejściowy. |
## Uwagi




```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) konstruktor


Ten konstruktor pobiera ścieżkę do pliku źródłowego, z którego odczytywana jest zawartość [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Plik wejściowy. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Dodatkowe opcje ładowania. |

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Presentation](../)
* Klasa [LoadOptions](../../loadoptions/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)