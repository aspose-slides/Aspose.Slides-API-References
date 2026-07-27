---
title: CheckWriteProtection()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se uma senha para modificar está correta para uma apresentação protegida contra gravação.
type: docs
weight: 66
url: /pt/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) método


Verifica se uma senha para modificar está correta para uma apresentação protegida contra gravação.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | A senha a ser verificada. |

### Valor de retorno

True se a apresentação estiver protegida contra gravação e a senha estiver correta. False caso contrário.
## Observações



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```



1. Você deve verificar a propriedade [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) antes de chamar este método.
1. Quando a senha for nula ou vazia, este método retornará false.



## Ver também

* Classe [String](../../../system/string/)
* Classe [IPresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)