---
title: Presentation()
second_title: Referencia de API de Aspose.Slides para C++
description: Este constructor crea una nueva presentación desde cero. La presentación creada tiene una diapositiva vacía.
type: docs
weight: 417
url: /es/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() constructor


Este constructor crea una nueva presentación desde cero. La presentación creada tiene una diapositiva vacía.

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) constructor


Este constructor crea una nueva presentación desde cero. La presentación creada tiene una diapositiva vacía.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Opciones de carga adicionales. |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) constructor


Este constructor es el mecanismo principal para leer un [Presentation](../) existente.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream de entrada. |
## Observaciones




```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) constructor


Este constructor es el mecanismo principal para leer un [Presentation](../) existente.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream de entrada. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Opciones de carga adicionales. |

## Presentation::Presentation(System::String) constructor


Este constructor obtiene la ruta del archivo fuente desde la cual se leen los contenidos del [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Archivo de entrada. |
## Observaciones




```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) constructor


Este constructor obtiene la ruta del archivo fuente desde la cual se leen los contenidos del [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Archivo de entrada. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Opciones de carga adicionales. |

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../)
* Class [LoadOptions](../../loadoptions/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)