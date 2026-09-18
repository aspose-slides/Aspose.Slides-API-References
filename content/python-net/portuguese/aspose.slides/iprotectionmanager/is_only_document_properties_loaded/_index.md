---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded propriedade
Esta propriedade faz sentido se o arquivo de apresentação estiver protegido por senha e as propriedades do documento desse arquivo forem públicas.
Valor true significa que somente as propriedades do documento são carregadas de um arquivo de apresentação criptografado sem o uso de senha.
Valor false significa que a apresentação inteira criptografada é carregada com o uso da senha correta, não apenas as propriedades do documento são carregadas.
Se a apresentação não estiver criptografada, então o valor da propriedade será sempre false.
Se as propriedades do documento de um arquivo criptografado não forem públicas, então o valor da propriedade será sempre false.
Se PresentationEx.EncryptDocumentProperties for true, então o valor da propriedade IsOnlyDocumentPropertiesLoaded será sempre false.
Somente leitura **bool**.

### Definição:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Veja Também
* classe [`IProtectionManager`](/slides/python-net/pt/aspose.slides/iprotectionmanager)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)