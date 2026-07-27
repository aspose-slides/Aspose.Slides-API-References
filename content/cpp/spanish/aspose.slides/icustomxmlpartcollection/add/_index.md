---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega una nueva parte xml personalizada.
type: docs
weight: 14
url: /es/aspose.slides/icustomxmlpartcollection/add/
---
## ICustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) método

Agrega una nueva parte xml personalizada.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Los datos xml de la nueva parte a agregar. |

### Valor de retorno

Parte xml personalizada creada.

## ICustomXmlPartCollection::Add(System::String) método

Agrega una nueva parte xml personalizada.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::String xmlString)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | La cadena xml de la nueva parte a agregar. |

### Valor de retorno

Parte xml personalizada creada.

## ICustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) método

Agrega una nueva parte xml personalizada.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | El flujo de entrada con datos xml de la nueva parte a agregar. |

### Valor de retorno

Parte xml personalizada creada.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [ICustomXmlPart](../../icustomxmlpart/)
* Clase [ICustomXmlPartCollection](../)
* Clase [String](../../../system/string/)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)