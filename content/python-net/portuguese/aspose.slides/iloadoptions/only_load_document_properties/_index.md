---
title: only_load_document_properties property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/iloadoptions/only_load_document_properties/
weight: 100
---
## only_load_document_properties propriedade
Esta propriedade faz sentido, se o arquivo de apresentação estiver protegido por senha.
            Valor true significa que apenas as propriedades do documento devem ser carregadas de um arquivo criptografado 
            e a senha deve ser ignorada.
            Valor false significa que a apresentação criptografada inteira deve ser carregada com o uso da senha correta 
            .
            Se a apresentação não estiver criptografada, o valor da propriedade será sempre ignorado.
            Se as propriedades do documento de um arquivo criptografado não forem públicas e o valor da propriedade for true então
            as propriedades do documento não podem ser carregadas e uma exceção será lançada.
Leitura e escrita **bool**.

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
* classe [`ILoadOptions`](/slides/python-net/pt/aspose.slides/iloadoptions)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)