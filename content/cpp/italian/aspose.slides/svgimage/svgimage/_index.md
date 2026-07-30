---
title: SvgImage()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo oggetto SvgImage.
type: docs
weight: 53
url: /it/aspose.slides/svgimage/svgimage/
---
## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>) costruttore

Crea un nuovo oggetto [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dati Svg. |

## SvgImage::SvgImage(System::String) costruttore

Crea un nuovo oggetto [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Contenuto Svg. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>) costruttore

Crea un nuovo oggetto [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flusso Svg. |

## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) costruttore

Crea un nuovo oggetto [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dati Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni saranno ignorati. |
| baseUri | [System::String](../../../system/string/) | URI di base dello Svg specificato. Usato per risolvere i collegamenti relativi. |

## SvgImage::SvgImage(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) costruttore

Crea un nuovo oggetto [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Contenuto Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni saranno ignorati. |
| baseUri | [System::String](../../../system/string/) | URI di base dello Svg specificato. Usato per risolvere i collegamenti relativi. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) costruttore

Crea un nuovo oggetto [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flusso Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni saranno ignorati. |
| baseUri | [System::String](../../../system/string/) | URI di base dello Svg specificato. Usato per risolvere i collegamenti relativi. |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [SvgImage](../)
* Classe [String](../../../system/string/)
* Classe [Stream](../../../system.io/stream/)
* Classe [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)