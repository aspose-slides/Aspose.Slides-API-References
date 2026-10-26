---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona nova parte xml personalizada.
type: docs
weight: 53
url: /pt/aspose.slides/customxmlpartcollection/add/
---
## CustomXmlPartCollection::Add(System::String) método


Adiciona nova parte xml personalizada.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::String xmlString) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | A string xml da nova parte a ser adicionada. |

### Valor de Retorno

Parte xml personalizada criada.

## CustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) método


Adiciona nova parte xml personalizada.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Os dados xml da nova parte a ser adicionada. |

### Valor de Retorno

Parte xml personalizada criada.

## CustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) método


Adiciona nova parte xml personalizada.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | O inputStream com dados xml da nova parte a ser adicionada. |

### Valor de Retorno

Parte xml personalizada criada.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICustomXmlPart](../../icustomxmlpart/)
* Classe [String](../../../system/string/)
* Classe [CustomXmlPartCollection](../)
* Classe [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)