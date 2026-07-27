---
title: CheckWriteProtection()
second_title: Referência da API Aspose.Slides para C++
description: Determina se uma apresentação está protegida por senha para modificação.
type: docs
weight: 157
url: /pt/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) método

Determina se uma apresentação está protegida por senha para modificação.

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | A senha para verificação. |

### Valor de Retorno

Verdadeiro se a senha for válida; caso contrário, falso.

## Observações

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. Você deve verificar a propriedade [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) antes de chamar este método.
1. Quando a senha for nula ou vazia, este método retorna falso.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [IProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)