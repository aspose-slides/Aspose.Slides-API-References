---
title: Presentation()
second_title: Aspose.Slides für C++ API-Referenz
description: Dieser Konstruktor erstellt eine neue Präsentation von Grund auf. Die erstellte Präsentation enthält eine leere Folie.
type: docs
weight: 417
url: /de/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() Konstruktor


Dieser Konstruktor erstellt eine neue Präsentation von Grund auf. Die erstellte Präsentation enthält eine leere Folie.

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) Konstruktor


Dieser Konstruktor erstellt eine neue Präsentation von Grund auf. Die erstellte Präsentation enthält eine leere Folie.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Zusätzliche Ladeoptionen. |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) Konstruktor


Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer bestehenden [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Eingabestream. |
## Anmerkungen




```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) Konstruktor


Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer bestehenden [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Eingabestream. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Zusätzliche Ladeoptionen. |

## Presentation::Presentation(System::String) Konstruktor


Dieser Konstruktor erhält einen Quellpfad, aus dem der Inhalt des [Presentation](../) gelesen wird.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Eingabedatei. |
## Anmerkungen




```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) Konstruktor


Dieser Konstruktor erhält einen Quellpfad, aus dem der Inhalt des [Presentation](../) gelesen wird.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Eingabedatei. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Zusätzliche Ladeoptionen. |

## Siehe Auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Presentation](../)
* Klasse [LoadOptions](../../loadoptions/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)