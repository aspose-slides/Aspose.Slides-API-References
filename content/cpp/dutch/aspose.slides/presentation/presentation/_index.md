---
title: Presentation()
second_title: Aspose.Slides voor C++ API Referentie
description: Deze constructor maakt een nieuwe presentatie vanaf nul. De aangemaakte presentatie heeft één lege dia.
type: docs
weight: 417
url: /nl/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() constructor


Deze constructor maakt een nieuwe presentatie vanaf nul. De aangemaakte presentatie heeft één lege dia.

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) constructor


Deze constructor maakt een nieuwe presentatie vanaf nul. De aangemaakte presentatie heeft één lege dia.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Aanvullende laadopties. |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) constructor


Deze constructor is het primaire mechanisme voor het lezen van een bestaande [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Invoerstroom. |
## Opmerkingen




```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) constructor


Deze constructor is het primaire mechanisme voor het lezen van een bestaande [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Invoerstroom. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Aanvullende laadopties. |

## Presentation::Presentation(System::String) constructor


Deze constructor krijgt een bestandspad van waar de inhoud van de [Presentation](../) wordt gelezen.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Invoerbestand. |
## Opmerkingen.




```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) constructor


Deze constructor krijgt een bestandspad van waar de inhoud van de [Presentation](../) wordt gelezen.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Invoerbestand. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Aanvullende laadopties. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Presentation](../)
* Klasse [LoadOptions](../../loadoptions/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)