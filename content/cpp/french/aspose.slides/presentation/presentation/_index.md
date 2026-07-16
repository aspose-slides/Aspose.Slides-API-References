---
title: Presentation()
second_title: Référence API Aspose.Slides pour C++
description: Ce constructeur crée une nouvelle présentation à partir de zéro. La présentation créée possède une diapositive vide.
type: docs
weight: 417
url: /fr/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() constructeur

Ce constructeur crée une nouvelle présentation à partir de zéro. La présentation créée possède une diapositive vide.

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) constructeur

Ce constructeur crée une nouvelle présentation à partir de zéro. La présentation créée possède une diapositive vide.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Options de chargement supplémentaires. |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) constructeur

Ce constructeur est le mécanisme principal pour lire un [Presentation](../) existant.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux d'entrée. |
## Remarques

```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) constructeur

Ce constructeur est le mécanisme principal pour lire un [Presentation](../) existant.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux d'entrée. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Options de chargement supplémentaires. |

## Presentation::Presentation(System::String) constructeur

Ce constructeur obtient le chemin du fichier source à partir duquel le contenu du [Presentation](../) est lu.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Fichier d'entrée. |
## Remarques

```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) constructeur

Ce constructeur obtient le chemin du fichier source à partir duquel le contenu du [Presentation](../) est lu.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Fichier d'entrée. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Options de chargement supplémentaires. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../)
* Class [LoadOptions](../../loadoptions/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)