---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega una matriz de bytes al almacén XmlPreloadedResolver y lo asigna a un URI. Si el almacén ya contiene una asignación para el mismo URI, la asignación existente se sobrescribe.
type: docs
weight: 79
url: /es/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) method

Agrega una matriz de bytes al almacén [XmlPreloadedResolver](../) y lo asigna a un URI. Si el almacén ya contiene una asignación para el mismo URI, la asignación existente se sobrescribe.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | El URI de los datos que se están agregando al almacén [XmlPreloadedResolver](../). |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Una matriz de bytes con los datos que corresponden al URI proporcionado. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Agrega una matriz de bytes al almacén [XmlPreloadedResolver](../) y lo asigna a un URI. Si el almacén ya contiene una asignación para el mismo URI, la asignación existente se sobrescribe.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | El URI de los datos que se están agregando al almacén [XmlPreloadedResolver](../). |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Una matriz de bytes con los datos que corresponden al URI proporcionado. |
| offset | **int32_t** | El desplazamiento en la matriz de bytes proporcionada donde comienzan los datos. |
| count | **int32_t** | El número de bytes a leer de la matriz de bytes, comenzando en el desplazamiento proporcionado. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) method

Agrega un Stream al almacén [XmlPreloadedResolver](../) y lo asigna a un URI. Si el almacén ya contiene una asignación para el mismo URI, la asignación existente se sobrescribe.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | El URI de los datos que se están agregando al almacén [XmlPreloadedResolver](../). |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Un Stream con los datos que corresponden al URI proporcionado. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) method

Agrega una cadena con datos precargados al almacén [XmlPreloadedResolver](../) y lo asigna a un URI. Si el almacén ya contiene una asignación para el mismo URI, la asignación existente se sobrescribe.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | El URI de los datos que se están agregando al almacén [XmlPreloadedResolver](../). |
| value | const [String](../../../system/string/)\& | Un [String](../../../system/string/) con los datos que corresponden al URI proporcionado. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Uri](../../../system/uri/)
* Class [XmlPreloadedResolver](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)