---
title: Encrypt()
second_title: Referência da API Aspose.Slides para C++
description: Criptografa a apresentação com a senha especificada.
type: docs
weight: 105
url: /pt/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) método

Criptografa [Presentation](../../presentation/) com a senha especificada.

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | A senha. |
## Observações

O código de exemplo a seguir mostra como criptografar um PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## Veja também

* Classe [String](../../../system/string/)
* Classe [ProtectionManager](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)