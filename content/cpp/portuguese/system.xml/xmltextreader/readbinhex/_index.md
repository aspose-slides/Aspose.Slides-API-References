---
title: ReadBinHex()
second_title: Referência da API Aspose.Slides para C++
description: Decodifica BinHex e retorna os bytes binários decodificados.
type: docs
weight: 781
url: /pt/system.xml/xmltextreader/readbinhex/
---
## XmlTextReader::ReadBinHex(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Decodifica **BinHex** e retorna os bytes binários decodificados.

```cpp
int32_t System::Xml::XmlTextReader::ReadBinHex(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array de bytes que serve como buffer para o qual os bytes binários decodificados são gravados. |
| offset | **int32_t** | O índice baseado em zero no array que especifica onde o método pode começar a gravar no buffer. |
| len | **int32_t** | O número de bytes a serem gravados no buffer. |

### Valor de Retorno

O número de bytes gravados no seu buffer.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)