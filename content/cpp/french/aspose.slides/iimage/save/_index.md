---
title: Save()
second_title: Référence API Aspose.Slides pour C++
description: Enregistre l'image dans un fichier.
type: docs
weight: 40
url: /fr/aspose.slides/iimage/save/
---
## IImage::Save(System::String) méthode

Enregistre l'image dans un fichier.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Le chemin du fichier où l'image sera enregistrée. |

## IImage::Save(System::String, ImageFormat) méthode

Enregistre l'image dans un fichier au format spécifié.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Le chemin du fichier où l'image sera enregistrée. |
| format | [ImageFormat](../../imageformat/) | Le format de l'image. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) méthode

Enregistre l'image dans un flux au format spécifié.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Le flux où l'image sera enregistrée. |
| format | [ImageFormat](../../imageformat/) | Le format de l'image. |

## IImage::Save(System::String, ImageFormat, int32_t) méthode

Enregistre l'image dans un fichier au format et à la qualité spécifiés.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Le chemin du fichier où l'image sera enregistrée. |
| format | [ImageFormat](../../imageformat/) | Le format de l'image. |
| quality | **int32_t** | La qualité de l'image enregistrée (0 à 100).  

 Ce paramètre n'affecte la sauvegarde que dans [ImageFormat::Jpeg](../../imageformat/) ; pour tous les autres formats, il est ignoré. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) méthode

Enregistre l'image dans un flux au format et à la qualité spécifiés.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Le flux où l'image sera enregistrée. |
| format | [ImageFormat](../../imageformat/) | Le format de l'image. |
| quality | **int32_t** | La qualité de l'image enregistrée (0 à 100).  

 Ce paramètre n'affecte la sauvegarde que dans [ImageFormat::Jpeg](../../imageformat/) ; pour tous les autres formats, il est ignoré. |

## Voir aussi

* Enum [ImageFormat](../../imageformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [String](../../../system/string/)
* classe [IImage](../)
* classe [Stream](../../../system.io/stream/)
* espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)