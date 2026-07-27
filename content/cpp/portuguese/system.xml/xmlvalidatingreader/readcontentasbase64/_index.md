---
title: ReadContentAsBase64()
second_title: Aspose.Slides para C++ Referência da API
description: Lê o conteúdo e retorna os bytes binários decodificados em Base64.
type: docs
weight: 573
url: /pt/system.xml/xmlvalidatingreader/readcontentasbase64/
---
## XmlValidatingReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) método

Lê o conteúdo e retorna os bytes binários decodificados em Base64.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O buffer no qual copiar o texto resultante. Este valor não pode ser **nullptr**. |
| index | **int32_t** | O deslocamento no buffer onde começar a copiar o resultado. |
| count | **int32_t** | O número máximo de bytes a copiar para o buffer. O número real de bytes copiados é retornado por este método. |

### Valor de Retorno

O número de bytes gravados no buffer.

## Ver Também

* typedef [ArrayPtr](../../../system/arrayptr/)
* classe [XmlValidatingReader](../)
* namespace [System::Xml](../../)
* biblioteca [Aspose.Slides](../../../)