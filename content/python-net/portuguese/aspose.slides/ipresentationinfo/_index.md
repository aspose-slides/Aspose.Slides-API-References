---
title: IPresentationInfo class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/ipresentationinfo/
---
## IPresentationInfo classe

Informação sobre o arquivo de apresentação

O tipo IPresentationInfo expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`is_encrypted`](/slides/python-net/pt/aspose.slides/ipresentationinfo/is_encrypted/) | Obtém True se a apresentação vinculada está criptografada, caso contrário False.<br/>            Somente leitura **bool**. |
| [`is_password_protected`](/slides/python-net/pt/aspose.slides/ipresentationinfo/is_password_protected/) | Obtém um valor que indica se a apresentação vinculada está protegida por uma senha para abrir. |
| [`is_write_protected`](/slides/python-net/pt/aspose.slides/ipresentationinfo/is_write_protected/) | Obtém um valor que indica se a apresentação vinculada está protegida contra gravação. |
| [`load_format`](/slides/python-net/pt/aspose.slides/ipresentationinfo/load_format/) | Obtém o formato da apresentação vinculada.<br/>            Somente leitura [`LoadFormat`](/slides/python-net/pt/aspose.slides/loadformat). |

## Métodos

| Método | Descrição |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/pt/aspose.slides/ipresentationinfo/write_binded_presentation/#iorawiobase) | Escreve a apresentação vinculada para o fluxo. |
| [`write_binded_presentation(self, file)`](/slides/python-net/pt/aspose.slides/ipresentationinfo/write_binded_presentation/#str) | Escreve a apresentação vinculada em um arquivo. |
| [`check_password(self, password)`](/slides/python-net/pt/aspose.slides/ipresentationinfo/check_password/#str) | Verifica se uma senha está correta para uma apresentação protegida com senha de abertura. |
| [`check_write_protection(self, password)`](/slides/python-net/pt/aspose.slides/ipresentationinfo/check_write_protection/#str) | Verifica se a senha para modificar está correta para uma apresentação protegida contra gravação. |
| [`read_document_properties(self)`](/slides/python-net/pt/aspose.slides/ipresentationinfo/read_document_properties/#) | Obtém as propriedades do documento da apresentação vinculada. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/pt/aspose.slides/ipresentationinfo/update_document_properties/#idocumentproperties) | Atualiza as propriedades da apresentação vinculada. |


### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)