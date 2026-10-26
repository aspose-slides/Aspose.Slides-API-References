---
title: CheckPassword()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se uma senha está correta para uma apresentação protegida com senha aberta.
type: docs
weight: 53
url: /pt/aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo::CheckPassword(System::String) método


Verifica se uma senha está correta para uma apresentação protegida com senha aberta.

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | A senha a ser verificada. |

### Valor de Retorno

Verdadeiro se a apresentação estiver protegida com senha aberta e a senha estiver correta e falso caso contrário.
## Observações



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```



Quando a senha é nula ou vazia, este método retorna falso. 

## Veja Também

* Classe [String](../../../system/string/)
* Classe [PresentationInfo](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)