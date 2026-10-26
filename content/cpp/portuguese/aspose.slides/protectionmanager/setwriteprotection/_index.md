---
title: SetWriteProtection()
second_title: Referência da API Aspose.Slides para C++
description: Define a proteção de escrita para esta apresentação com a senha especificada.
type: docs
weight: 131
url: /pt/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) método


Define a proteção de escrita para esta apresentação com a senha especificada.

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | A senha. |
## Observações



O código de exemplo a seguir mostra como definir a proteção de escrita de uma apresentação. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## Veja Também

* Classe [String](../../../system/string/)
* Classe [ProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)