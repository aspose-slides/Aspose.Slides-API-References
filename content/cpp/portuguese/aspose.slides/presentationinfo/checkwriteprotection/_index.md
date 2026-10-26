---
title: CheckWriteProtection()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se a senha para modificar está correta para uma apresentação protegida contra gravação.
type: docs
weight: 66
url: /pt/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) method

Verifica se uma senha para modificar está correta para uma apresentação protegida contra gravação.

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```

### Argumentos

| Parameter | Type | Description |
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

1. Você deve verificar a propriedade [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) antes de chamar este método.
1. Quando a senha for nula ou vazia, este método retorna false

## Veja também

* Classe [String](../../../system/string/)
* Classe [PresentationInfo](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)