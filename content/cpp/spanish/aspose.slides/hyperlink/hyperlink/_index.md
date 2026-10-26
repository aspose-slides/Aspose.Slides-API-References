---
title: Hyperlink()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea una instancia de un hipervínculo.
type: docs
weight: 339
url: /es/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) constructor

Crea una instancia de un hipervínculo.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) constructor

Crea una instancia de un hipervínculo que apunta a una diapositiva específica. Nota: el hipervínculo creado debe asignarse a algún objeto de la misma presentación, de lo contrario el enlace se guardará como NoAction.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Diapositiva de destino. |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) constructor

Crea una instancia de un hipervínculo usando otro hipervínculo como origen, sobrescribiendo propiedades secundarias.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | Hipervínculo de origen |
| targetFrame | [System::String](../../../system/string/) | Marco de destino |
| tooltip | [System::String](../../../system/string/) | Texto de información sobre herramientas |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Hyperlink](../)
* Class [ISlide](../../islide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)