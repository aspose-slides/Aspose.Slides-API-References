---
title: Add()
second_title: Aspose.Slides para C++ Referência da API
description: Adiciona nova parte xml personalizada.
type: docs
weight: 14
url: /pt/aspose.slides/icustomxmlpartcollection/add/
---
## ICustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) método


Adds new custom xml part.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The xml data of new part to be added. |

### Valor de Retorno

Created custom xml part.

## ICustomXmlPartCollection::Add(System::String) método


Adds new custom xml part.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::String xmlString)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | The xml string of new part to be added. |

### Valor de Retorno

Created custom xml part.

## ICustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) método


Adds new custom xml part.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | The inputStream with xml data of new part to be added. |

### Valor de Retorno

Created custom xml part.

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICustomXmlPart](../../icustomxmlpart/)
* Class [ICustomXmlPartCollection](../)
* Class [String](../../../system/string/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)