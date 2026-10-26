---
title: CheckWriteProtection()
second_title: Referência da API Aspose.Slides para C++
description: Determina se uma apresentação está protegida por senha para ser modificada.
type: docs
weight: 157
url: /pt/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) method


Determina se uma apresentação está protegida por senha para ser modificada.

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```


### Argumentos

| Parámetro | Tipo | Descrição |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | A senha para verificação. |

### Valor de Retorno

True se a senha for válida; caso contrário, false.
## Observações



```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```



1. Você deve verificar a propriedade [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) antes de chamar este método.
1. Quando a senha é nula ou vazia, este método retorna false.


## Veja Também

* Classe [String](../../../system/string/)
* Classe [ProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)