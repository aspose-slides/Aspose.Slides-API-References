---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega una nueva parte xml personalizada.
type: docs
weight: 53
url: /es/aspose.slides/customxmlpartcollection/add/
---
## CustomXmlPartCollection::Add(System::String) método


Agrega una nueva parte xml personalizada.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::String xmlString) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | La cadena xml de la nueva parte a agregar. |

### Valor devuelto

Parte xml personalizada creada.

## CustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) método


Agrega una nueva parte xml personalizada.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Los datos xml de la nueva parte a agregar. |

### Valor devuelto

Parte xml personalizada creada.

## CustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) método


Agrega una nueva parte xml personalizada.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | El inputStream con datos xml de la nueva parte a agregar. |

### Valor devuelto

Parte xml personalizada creada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICustomXmlPart](../../icustomxmlpart/)
* Class [String](../../../system/string/)
* Class [CustomXmlPartCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)