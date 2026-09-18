---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded propriedade
Esta propriedade faz sentido, se o arquivo de apresentação estiver protegido por senha e o documento 
            propriedades deste arquivo são públicas.
Valor true significa que apenas as propriedades do documento são carregadas de um 
            arquivo de apresentação criptografado sem uso de senha.
Valor false significa que toda a apresentação criptografada é carregada com o uso da senha 
            correta, não apenas as propriedades do documento são carregadas.
Se a apresentação não estiver criptografada então o valor da propriedade é sempre false.
Se as propriedades do documento de um arquivo criptografado não forem públicas então o valor da propriedade é sempre false.
Se Presentation.EncryptDocumentProperties for true então IsOnlyDocumentPropertiesLoaded 
            valor da propriedade é sempre false.
Somente leitura **bool**.

### Definição:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Ver Também
* classe [`ProtectionManager`](/slides/python-net/pt/aspose.slides/protectionmanager)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)