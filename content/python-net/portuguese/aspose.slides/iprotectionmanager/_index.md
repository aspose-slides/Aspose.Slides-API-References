---
title: IProtectionManager class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/iprotectionmanager/
---
## IProtectionManager classe

Gerenciamento da proteção por senha da apresentação.

O tipo IProtectionManager expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/pt/aspose.slides/iprotectionmanager/encrypt_document_properties/) | Esta propriedade faz sentido se a apresentação estiver protegida por senha.<br/>Se for true então as propriedades do documento são criptografadas no arquivo de apresentação.<br/>Se for false então as propriedades do documento são públicas enquanto a apresentação está criptografada.<br/>Leitura/gravação **bool**. |
| [`is_encrypted`](/slides/python-net/pt/aspose.slides/iprotectionmanager/is_encrypted/) | Obtém um valor que indica se esta instância está criptografada.<br/>Somente leitura **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/pt/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | Esta propriedade faz sentido se o arquivo de apresentação estiver protegido por senha e as propriedades do documento deste arquivo forem públicas.<br/>Valor true significa que apenas as propriedades do documento são carregadas de um arquivo de apresentação criptografado sem o uso de senha.<br/>Valor false significa que toda a apresentação criptografada é carregada com o uso da senha correta, não apenas as propriedades do documento são carregadas.<br/>Se a apresentação não estiver criptografada, então o valor da propriedade é sempre false.<br/>Se as propriedades do documento de um arquivo criptografado não forem públicas, então o valor da propriedade é sempre false.<br/>Se PresentationEx.EncryptDocumentProperties for true, então o valor da propriedade IsOnlyDocumentPropertiesLoaded é sempre false.<br/>Somente leitura **bool**. |
| [`is_write_protected`](/slides/python-net/pt/aspose.slides/iprotectionmanager/is_write_protected/) | Obtém um valor que indica se esta apresentação está protegida contra gravação.<br/>Somente leitura **bool**. |
| [`encryption_password`](/slides/python-net/pt/aspose.slides/iprotectionmanager/encryption_password/) | Retorna a senha de criptografia.<br/>Somente leitura **str**. |
| [`read_only_recommended`](/slides/python-net/pt/aspose.slides/iprotectionmanager/read_only_recommended/) | Obtém ou define a recomendação de somente leitura.<br/>Leitura/gravação **bool**. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/pt/aspose.slides/iprotectionmanager/encrypt/#str) | Criptografa a Apresentação com a senha especificada. |
| [`remove_encryption(self)`](/slides/python-net/pt/aspose.slides/iprotectionmanager/remove_encryption/#) | Remove a criptografia. |
| [`set_write_protection(self, password)`](/slides/python-net/pt/aspose.slides/iprotectionmanager/set_write_protection/#str) | Define a proteção contra gravação para esta apresentação com a senha especificada. |
| [`remove_write_protection(self)`](/slides/python-net/pt/aspose.slides/iprotectionmanager/remove_write_protection/#) | Remove a proteção contra gravação desta apresentação. |
| [`check_write_protection(self, password)`](/slides/python-net/pt/aspose.slides/iprotectionmanager/check_write_protection/#str) | Determina se uma apresentação está protegida por senha para modificação. |

### Ver também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)