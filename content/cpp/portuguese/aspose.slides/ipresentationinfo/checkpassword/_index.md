---
title: CheckPassword()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se uma senha está correta para uma apresentação protegida com senha aberta.
type: docs
weight: 53
url: /pt/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) método


Verifica se uma senha está correta para uma apresentação protegida com senha aberta.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | A senha a ser verificada. |

### Valor de Retorno

True se a apresentação estiver protegida com senha aberta e a senha estiver correta e false caso contrário.
## Observações



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```



Quando a senha for nula ou vazia, este método retorna false. 
## Veja Também

* Classe [String](../../../system/string/)
* Classe [IPresentationInfo](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)