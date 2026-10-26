---
title: only_load_document_properties property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/loadoptions/only_load_document_properties/
weight: 110
---
## only_load_document_properties propriedade
Esta propriedade faz sentido, se o arquivo de apresentação estiver protegido por senha.
            Valor true significa que apenas as propriedades do documento devem ser carregadas de um arquivo de apresentação criptografado e a senha deve ser ignorada.
            Valor false significa que a apresentação inteira criptografada deve ser carregada usando a senha correta.
            Se a apresentação não estiver criptografada, então o valor da propriedade é sempre ignorado.
            Se as propriedades do documento de um arquivo criptografado não forem públicas e o valor da propriedade for true, então as propriedades do documento não poderão ser carregadas e uma exceção será lançada.
            Leitura/Gravação **bool**.

### Definição:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```


### Veja Também
* classe [`LoadOptions`](/slides/python-net/pt/aspose.slides/loadoptions)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)