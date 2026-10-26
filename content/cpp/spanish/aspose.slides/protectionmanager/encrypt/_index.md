---
title: Encrypt()
second_title: Referencia de API de Aspose.Slides para C++
description: Encripta la presentación con la contraseña especificada.
type: docs
weight: 105
url: /es/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) método

Encripta [Presentation](../../presentation/) con la contraseña especificada.

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | La contraseña. |

## Observaciones

El siguiente código de ejemplo muestra cómo cifrar un PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [ProtectionManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)