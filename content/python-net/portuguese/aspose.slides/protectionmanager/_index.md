---
title: ProtectionManager class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/protectionmanager/
---
## ProtectionManager classe

Gerenciamento de proteção por senha da apresentação.

O tipo ProtectionManager expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/pt/aspose.slides/protectionmanager/encrypt_document_properties/) | Esta propriedade faz sentido se a apresentação estiver protegida por senha.<br/>            Se verdadeiro, então as propriedades do documento são criptografadas no arquivo de apresentação.<br/>            Se falso, então as propriedades do documento são públicas enquanto a apresentação está criptografada.<br/>            Leitura/Gravação **bool**. |
| [`is_encrypted`](/slides/python-net/pt/aspose.slides/protectionmanager/is_encrypted/) | Obtém um valor que indica se esta instância está criptografada.<br/>            Somente leitura **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/pt/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | Esta propriedade faz sentido se o arquivo de apresentação estiver protegido por senha e as propriedades do documento deste arquivo forem públicas.<br/>            Valor verdadeiro significa que apenas as propriedades do documento são carregadas a partir de um arquivo de apresentação criptografado sem uso de senha.<br/>            Valor falso significa que toda a apresentação criptografada é carregada com o uso da senha correta, não apenas as propriedades do documento são carregadas.<br/>            Se a apresentação não estiver criptografada, então o valor da propriedade é sempre falso.<br/>            Se as propriedades do documento de um arquivo criptografado não forem públicas, então o valor da propriedade é sempre falso.<br/>            Se Presentation.EncryptDocumentProperties for verdadeiro, então o valor da propriedade IsOnlyDocumentPropertiesLoaded é sempre falso.<br/>            Somente leitura **bool**. |
| [`is_write_protected`](/slides/python-net/pt/aspose.slides/protectionmanager/is_write_protected/) | Obtém um valor que indica se esta apresentação está protegida contra gravação.<br/>            Somente leitura **bool**. |
| [`encryption_password`](/slides/python-net/pt/aspose.slides/protectionmanager/encryption_password/) | Obtém a senha utilizada para a criptografia da apresentação.<br/>            Somente leitura **str**. |
| [`read_only_recommended`](/slides/python-net/pt/aspose.slides/protectionmanager/read_only_recommended/) | Obtém ou define a recomendação de somente leitura.<br/>            Leitura/Gravação **bool**. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/pt/aspose.slides/protectionmanager/encrypt/#str) | Criptografa a apresentação com a senha especificada. |
| [`remove_encryption(self)`](/slides/python-net/pt/aspose.slides/protectionmanager/remove_encryption/#) | Remove a criptografia. |
| [`set_write_protection(self, password)`](/slides/python-net/pt/aspose.slides/protectionmanager/set_write_protection/#str) | Define proteção contra gravação para esta apresentação com a senha especificada. |
| [`remove_write_protection(self)`](/slides/python-net/pt/aspose.slides/protectionmanager/remove_write_protection/#) | Remove a proteção contra gravação desta apresentação. |
| [`check_write_protection(self, password)`](/slides/python-net/pt/aspose.slides/protectionmanager/check_write_protection/#str) | Determina se uma apresentação está protegida por senha para modificação. |

### Veja também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)