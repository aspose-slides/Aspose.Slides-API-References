---
title: Save()
second_title: Aspose.Slides para C++ Referencia de API
description: Guarda el documento XML en el archivo especificado. Si el archivo especificado existe, este método lo sobrescribe.
type: docs
weight: 534
url: /es/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) método

Guarda el documento XML en el archivo especificado. Si el archivo especificado existe, este método lo sobrescribe.

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | [String](../../../system/string/) | La ubicación del archivo donde desea guardar el documento. |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) método

Guarda el documento XML en el flujo especificado.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | El flujo al que desea guardar. |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) método

Guarda el documento XML en el TextWriter especificado.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | El TextWriter al que desea guardar. |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) método

Guarda el documento XML en el [XmlWriter](../../xmlwriter/) especificado.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | El [XmlWriter](../../xmlwriter/) al que desea guardar. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlWriter](../../xmlwriter/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)