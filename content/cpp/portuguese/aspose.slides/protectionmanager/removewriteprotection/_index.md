---
title: RemoveWriteProtection()
second_title: Referência da API Aspose.Slides para C++
description: Remove a proteção contra gravação desta apresentação.
type: docs
weight: 144
url: /pt/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() método

Remove a proteção contra gravação desta apresentação.

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## Observações

Este código de exemplo mostra como remover a proteção contra gravação de um PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## Veja Também

* Classe [ProtectionManager](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)